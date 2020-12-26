rest-api-mongodb with oauth2
==============

simple node.js express rest-api with user authentication oauth2 jsonwebtoken. more routes and controllers can be added individualy to the needs of the app
MongoDB has to be installed.
Adjust uri in app.js, set ENV variables for JWT_KEY on cloud or server side.
Same value for JWT_KEY needs to be filled into files controllers/auth.js and router/user.js
Server Port needs to be defined in server.js, and manifest.yml needs to be adapted and then the app can be run localy or deployed to cloud foundry or other clouds, start it with command node server.js

use localhost:3300/v1/user/signup route to signup a new user
use localhost:3300/v1/user/login route to login

add more routes and controllers to your needs







