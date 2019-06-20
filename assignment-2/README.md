***Assignment 2***

**Run application in terminal**

cd into assignment-2 dir
NODE_ENV=staging node index.js 

**Create User**

POST localhost:3000/users

body: {
	"firstName": "Anna",
	"lastName": "Casper",
	"email": "anna@spiredigital.com",
	"streetAddress": "940 Lincoln St."
	"password": "password"
}

**Get User**

GET localhost:3000/users?email=anna@spiredigital.com

headers: {token: token}

**Update User**

PUT localhost:3000/users

headers: {token: token}

body: {
	"firstName": "Anna1",
	"lastName": "Casper1",
	"email": "anna@spiredigital.com",
	"streetAddress": "941 Lincoln St."
	"password": "password"
}

**Delete User** 

DELETE localhost:3000/users?email=anna@spiredigital.com

**Create Token**

POST localhost:3000/tokens

body: {
	"email": "anna@spiredigital.com",
	"password": "password"
}

**Get Token**

GET localhost:3000/tokens?id={id}

**Update Token**

PUT localhost:3000/tokens

body: {
    "id": "xft1r0h5mkfnts85vc08",
    "extend": true
}

**Delete Token**

DELETE localhost:3000/tokens?id={id}