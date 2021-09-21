# jwt

First download the zip file 

Then Use eclipse IDE to see and run the code

First thing in application.properties file change your local mysql database name where I mentioned database name in spring.datasource.url line
Then after give your database username and password

In Postman tool use http://localhost:8080/register to create username and password

In JSON format in Body tab example: "username":"user1", "password":"password". 
It will return username and encoded password.

In Postman tool use http://localhost:8080/getcount for public API

In Postman tool use http://localhost:8080/login with JSON format in Body tab example: "username":"user1", "password":"password"
It will return token copy and paste it in Authorization tab Type Bearer Token paste it on right side

In Postman tool use http://localhost:8080/getdata for private API
It will return all record of user table.

