mvn jetty:run

login
http://localhost:8080/registration/rest/user/login?id=root&password=qwerty            
will return session token

get all users
http://localhost:8080/registration/rest/user?token=<token>

get user
http://localhost:8080/registration/rest/user/<id>?token=<token>
