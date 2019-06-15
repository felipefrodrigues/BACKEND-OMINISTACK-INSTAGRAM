# BACKEND-OMINISTACK-INSTAGRAM
Aplicacao em node com mongodb, para armazenar posts igual no instagram, com upload de imagem e uma rota que permite curtir os posts


npm install
npm start

POST http://localhost:3333/posts - multpartForm
image - file,
author - string ,
place - string,
description - string
hashtags - string

GET http://localhost:3333/posts


### LIKE
POST http://localhost:3333/posts/IDPOST/like 

http://localhost:3333/posts/5d0507d43f60ef075cc7a86a/like
