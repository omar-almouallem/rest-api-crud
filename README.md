# CRUD Rest API 
 About: <br />
 A Node.js REST API built with Express and Typescript

# How to run
## To build your server:
1- `npm install`<br />
2- `npm run build`<br />
3- `npm run start`
## To test your server locally:
1- `npm install`<br />
2- `npm run dev`

# Hot to use

Users:<br />
create user : localhost:3000/users<br />
(Content-Type: application/json)<br />
{<br />
  "firstName": ,<br />
  "lastName":  ,<br />
  "age":<br />
}<br />
get user : localhost:3000/users/(userID)<br />

update user : localhost:3000/user/(userID)<br />
(Content-Type: application/json)<br />
{ <br />
  "firstName": ,<br />
  "lastName":  ,<br />
  "age":<br />
}<br />

delete user : localhost:3000/user/(userID)

