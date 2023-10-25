# dummyServer
Server to call and create users stored in memory.

Three endpoints:
* GET /reset
* POST /users --> Body {"username": <mandatory field>, "name": <optional field>}
* GET /users or /users/<user_id>

Here a POC: https://dummyserver-9qa2.onrender.com
