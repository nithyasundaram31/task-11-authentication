1) Explanation of authentication and autharization :
The application is developed to implement the user authentication and autharization using the bearer token.
2) First the user register the details name, email, password in the request body by the api endpoins in the postman. it store the information in the database.

3) User login the page to give the email and password.once login is successful will generate the token.

4)If user logout the app .We should attach the bearer token with this request to logout.If an unauthorized user send this request, it will get an unauthorize message.

5) If the user want to  see the profile database. We should attach the bearer token with this request to get the details. If an unauthorized user send this request, it will get an unauthorize message. 

postman documentation url:
https://documenter.getpostman.com/view/44309120/2sB2j3CY3D

Technologies used:
-mongoose 
-express
-dotenv
-bcrypt
-jsonwebtoken 

Render Api end points:
https://task-11-authentication-2.onrender.com/users/register
https://task-11-authentication-2.onrender.com/users/login
https://task-11-authentication-2.onrender.com/users/logout
https://task-11-authentication-2.onrender.com/users/me

