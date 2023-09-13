
mkdir name-it-anything  -> to create a new folder in Bush
cd in that folder
npm init -y -> to create a package.JSON
npm install

change script: in package.json:
"scripts": {
    "dev": "nodemon index.js",
    "start": "node index.js"
  },


(node index.js - to console log in bash terninal)
added nodemoon - npm i nodemode -D
npm run dev (to see how its run the changes in Bash) - press ctrl C - to exit this server mood


Express.js, which is a popular and widely-used web application framework for Node.js. Express.js simplifies the process of building robust and scalable web applications and APIs by providing a set of features and tools to handle common tasks, such as routing, middleware, and handling HTTP requests and responses.

then do -->  npm install express (not as  dev)
add this to package.json:

  "dependencies": {
    "cors": "^2.8.5",
    "dotenv": "^16.3.1",
    "express": "^4.18.2"
  }

   then in terminal Bash --> npm install dotenv


on render:
runtime - Node
bild command - npm install
then go to Environment Variables:
put in key -  PORT, value - 4000




check main terminal, check server, if server crashed - you need to restart it

API testing tool - Thunder client