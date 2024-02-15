# 5sem-IA
FIRST install all the dependencies

npm install in the project directory.
Start Server:

Execute npm start or nodemon app.js in the project directory.
Open Postman:

Launch the Postman application.
Test Endpoints:

Login Endpoint:

Method: POST
URL: http://localhost:3000/auth/login
Register Endpoint:

Method: POST
URL: http://localhost:3000/auth/register
Create New Blog:

Method: POST
URL: http://localhost:3000/blogs
Body (JSON): {"authorId":1,"title": "New Blog", "content": "Lorem ipsum..."}
Retrieve All Blogs:

Method: GET
URL: http://localhost:3000/blogs
Retrieve Blog by Author ID:

Method: GET
URL: http://localhost:3000/blogs/{authorId}
