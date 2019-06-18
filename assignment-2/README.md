***Assignment 2***

**Run application in terminal**

cd into assignment-2 dir
NODE_ENV=staging node index.js 

**Create User**

POST localhost:3000/users
{
	"firstName": "Anna",
	"lastName": "Casper",
	"email": "anna@spiredigital.com",
	"streetAddress": "940 Lincoln St."
	"password": "password"
}