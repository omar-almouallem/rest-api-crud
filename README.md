# CRUD Rest API 
 About: 
 A Node.js REST API built with Express and Typescript

# How to run
## To build your server:
1- `npm install`
2- `npm run build`
3- `npm run start`
## To test your server locally:
1- `npm install`<br />
2- `npm run dev`

# Hot to use

Users:
create user : localhost:3000/users
(Content-Type: application/json)
{
  "firstName": ,
  "lastName":  ,
  "age":
}
get user : localhost:3000/users/(userID)

update user : localhost:3000/user/(userID)
(Content-Type: application/json)
{ 
  "firstName": ,
  "lastName":  ,
  "age":
}

delete user : localhost:3000/user/(userID)

