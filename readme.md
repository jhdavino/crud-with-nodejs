This is a little example of RESTful CRUD in Node.js and mySQL.


## Installation
*for newbies : Clone or download zip to your machine then hit this :

    cd rest-crud-nodejs

then

    npm install

## Configuration (database)
server.js

        host: 'localhost',
        user: 'root',
        password : 'root',
        port : 3306, //port mysql
        database:'test'	


	
You're gonna need to create a DB named 'test' or whatever you name it,  import t_user.sql


## Open your Browser
And type: localhost:3000/api/user
