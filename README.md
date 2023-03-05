# Tutorials_CRUD
Node.js API server, using MySql and Express

clone the repo
cd to Tutorials_CRUD folder

Open the Tutorials_CRUD from a IDE (vsCode or any other IDE)
edit config/db.config.js with your DB configurations

npm install mysql cors express --save
node server.js (to start the server)

server will be running on http://localhost:8080/

Create a table in your database with following 
CREATE TABLE IF NOT EXISTS `tutorials` (
  id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
  title varchar(255) NOT NULL,
  description varchar(255),
  published BOOLEAN DEFAULT false
) ENGINE=InnoDB DEFAULT CHARSET=utf8;


Following is the turotial referred
https://www.bezkoder.com/node-js-rest-api-express-mysql/


