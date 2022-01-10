# Node-user-authentication-api
 microserviço de autenticação que poderá compor a sua caixinha de ferramentas e ser muito útil no seu dia a dia.
# Microserviço de autenticação com Nodejs

Este é um projeto desenvolvido durante estudo de node.js

Neste projeto criei **microserviço de autenticação** que poderá compor a sua caixinha de ferramentas e ser muito útil no seu dia a dia. :hammer::wrench:

## Composição do  projeto

Neste projeto Tem alguns **Endpoints Base** que podem ser extendidos da forma mais adequada para seu contexto. 

São eles:

### Usuários

* GET /users
* GET /users/:uuid
* POST /users
* PUT /users/:uuid
* DELETE /users/:uuid

### Autenticação

* POST /token
* POST /token/validate
