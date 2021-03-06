# postgres-1

Create a new repository for this project.

You'll recognize the service endpoints in this project challenge from one you previously did. You will create another RESTful API in Express which meets the below processing requirements. But, this time, instead of using in-memory data storage, you will connect your Express API to a Postgres database so that your data persists.

# Service endpoints:

🔺 GET student - returns a list of all students

🔺 GET students/:studentId - returns details of a specific student by student id

🔺 GET student?search= - returns a list of students filtered on name matching the given query

🔺 GET grades/:studentId - returns all grades for a given student by student id

🔺 POST grade - records a new grade, returns success status in JSON response and stores the new grade in the database

🔺 POST register - creates a new user, returns success status in JSON response and stores the new user in the database