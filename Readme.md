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
criar servidor express<br>
	const express = require("express")<br>
	cost app = express()<br>
	app.use(express.json())<br>
	app.metodo('/',(req, res)=>{<br>
		return res.json({})<br>
	app.listen(NNNN) <br>
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


