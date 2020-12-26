rest-api-mongodb with oauth2
==============

simple rest-api with user oauth2 jsonwebtoken more routes and controllers can be added individually
Adjust uri in app.js, set ENV variables for JWT_KEY on cloud or server side.
Same value for JWT_KEY needs to be filled in in files controllers/auth.js and router/user.js
Server Port need to be defined in server.js, and manifest.yml needs to be adapted and then the app can be run localy or deployed to cloud foundry e.g.





