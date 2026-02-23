📘 Student Management API
🎯 Objective

The objective of this project is to build a RESTful Student Management API using Node.js and Express.
The API performs basic operations such as retrieving students, calculating averages, filtering by branch, and more.

This project demonstrates:

REST API design

Route parameters

Array operations (map, filter, reduce)

Proper HTTP status handling

Clean backend structure


🚀 Implemented Routes
Method	Route	Description
GET	/students/topper	Returns student with highest CGPA
GET	/students/average	Returns average CGPA of all students
GET	/students/count	Returns total number of students
GET	/students/:id	Returns student by ID
GET	/students/branch/:branchName	Returns students from specific branch

🌐 Sample API URLs

Assuming server runs on port 3000:

http://localhost:3000/students/topper <br>
http://localhost:3000/students/average <br>
http://localhost:3000/students/count <br>
http://localhost:3000/students/3  <br>
http://localhost:3000/students/branch/CSE <br>


🛠 Steps to Run Locally

1️⃣ Clone the repository

git clone https://github.com/your-username/student-api.git

2️⃣ Navigate into project folder

cd student-api

3️⃣ Install dependencies

npm install

4️⃣ Start the server

node server.js

OR (if using nodemon):

npx nodemon server.js

5️⃣ Open browser or Postman:

http://localhost:3000

