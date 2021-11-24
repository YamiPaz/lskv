#lskv

Integrantes:
Bardin, Ignacio
Bulich, Yamila
Lepez, Martin



npx sequelize model:generate --name Color --attributes name:string

npx sequelize model:generate --name Size --attributes name:string

npx sequelize model:generate --name Brand --attributes name:string

npx sequelize model:generate --name Category --attributes name:string



npx sequelize model:generate --name Product --attributes name:string,description:string,price:decimal,stock:integer,brandId:integer,categoryId:integer,sizeId:integer,colorId:integer

npx sequelize model:generate --name Image --attributes name:string,productId:integer

npx sequelize model:generate --name Review --attributes name:string,description:string,mark:integer,product_id:integer
