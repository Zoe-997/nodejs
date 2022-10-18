open cmd windows

npm init
fill description, keyworks, author
npm install --save express
npm install --save socket.io
npm install --save nodemon / npm install --save-dev nodemon  /  npm install -g nodemon
nodemon serve.js

if nodemon don't run

in json add:
"scripts": {
    "serve": "nodemon server.js"
 }

npm run serve