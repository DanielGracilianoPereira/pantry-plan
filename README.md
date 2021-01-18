Autentication Process

client -> Send my content, this is my login and this is my password -> server
server -> Hey DB, Are this login and password match ? -> DB
DB -> Yes, they there are in here and match -> server
server -> OK send the content of this login and password -> DB
DB -> I use password to decript the content, here is this -> server
server -> Awsome now storege this token with this login in sections open -> DB
DB -> OK token and login stored -> server
server -> Take your content and token, have a good section -> client

Alter Content Autentication Process

client -> Change this content, my login is this and my token is this -> server
server -> Hey DB, there are any section with this login and this token ? -> DB
DB -> Yes, there are -> server
server -> Take this content, this login and this password and overwrite the current content associate with this login-> DB
DB -> Ok it's done -> server
server -> The content was changed -> client
