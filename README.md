# CRUD Rest API 
 About:A Node.js REST API built with Express and Typescript

# How to run

## Script:
To test your server locally:
`npm run dev`
To build your server:
`npm run build`
To start your server:
`npm run start`

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

