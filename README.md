This is a simple todo list application that allows users to create, read, update,
and delete todo lists and their associated items. 
The application is built using HTML, CSS, and JavaScript on the frontend, 
and it communicates with a backend API to perform CRUD operations on the todo data.

**Getting Started**
To run the todo list application locally, follow these steps:

**Clone the repository:**
git clone https://github.com/Jonathan-321/A-Task_App_manager.git

**Configure the backend API:**

Make sure you have Apache and MySQL database set up and running.
Update the API endpoints in the JavaScript code to match your server configuration.
Set up the database:
Create a new MySQL database for the todo list application.
Import the provided SQL schema to create the necessary tables.
Start the application:
Open the todo-list.html file in a web browser to access the todo list application.
Deployment
The todo list application can be deployed to a web server or hosting platform of your choice. 
In this case, the application was successfully deployed and tested on an Amazon EC2 instance.

**To deploy the application to an EC2 instance:**

Launch a new EC2 instance and configure the necessary security groups.
Connect to the EC2 instance using SSH.
Install Apache and MySQL on the instance.
Clone the repository or upload the application files to the instance.
Configure the backend API and database connection settings.
Start the Apache web server and ensure the application is accessible via the instance's public IP or domain name.

**Challenges**

Configuring Apache and MySQL on the EC2 instance required careful attention to security settings 
and file permissions.
Ensuring proper communication between the frontend and backend components involved testing 
and debugging API endpoints and request/response formats.

**Acknowledgements**

The todo list application was developed as a learning project and was inspired 
by various online tutorials and resources. Special thanks to Oklahoma Christian University for 
providing the backend API documentations that made the development process smoother.
