<h1>Roteiro para ativação de um app express</Hh1>

start yarn -y
--------------------
yarn add express
  yarn add nodemon -D
-----------------------------
criar um script em package.json
	"scripts": {
    "dev": "nodemon src/server.js"
  }
-----------------------------------------
criar servidor express
	const express = require("express")
	cost app = express()
	app.use(express.json())
	app.metodo('/',(req, res)=>{
		return res.json({});
	app.listen(NNNN) 
-----------------------------------------
Métodos http<br>
  GET - busca de iformação dentro do servidor<br>
  POST - Inserir uma informação no sevidor<br>
  PUT - Alterar uma informação no servidor<br>
  PATCH - Alterar uma informação específica<br>
  DELETE- Deleta uma informação do servidor<br>
-------------------------------------------

  Route /url/params<br>
	meio de identificação para editar/buscar/deletar algum recurso<br>
  Query <br>
	paginação, filtro<br>
  Body <br>
	objetos de inserção ou alteração de determinado recurso
------------------------------------------


