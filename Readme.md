1 git init
  .gitignore
-------------------
2 start yarn -y
--------------------
3 yarn add express
  yarn add nodemon -D
-----------------------------
4 criar um script em package.json
	"scripts": {
    "dev": "nodemon src/server.js"
  }
-----------------------------------------
5 criar servidor express
	const express = require("express")
	cost app = express()
	app.use(express.json())
	app.metodo('/',(req, res)=>{
		return res.json({});
	app.listen(NNNN) 
------------------------------------------
6 Métodos http
  GET - busca de iformação dentro do servidor
  POST - Inserir uma informação no sevidor
  PUT - Alterar uma informação no servidor
  PATCH - Alterar uma informação específica
  DELETE- Deleta uma informação do servidor
-------------------------------------------
7 Parametros

  Route /url/params
	meio de identificação para editar/buscar/deletar algum recurso
  Query 
	paginação, filtro
  Body 
	objetos de inserção ou alteração de determinado recurso
------------------------------------------


