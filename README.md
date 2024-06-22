# MERN-Application

Sample MERN Stack Application

Welcome to the Sample MERN Stack Application! This project demonstrates a comprehensive implementation of a full-stack web application using the MERN stack, which includes MongoDB, Express, React, and Node.js. Additionally, the project incorporates Sequel for backend management in some areas and EJS templates for certain front-end views. The application showcases the creation, reading, updating, and deletion (CRUD) operations, with a focus on real-time error handling and a user-friendly interface.

What is MERN
- M – Mern
- E – Express
- R – React
- N -Node

![download](https://github.com/shwetak28/MERN-Application/assets/139232353/ebe4b84a-020c-4f15-8506-7966bb51a34e)

Table of Contents                                                                                                                                          
1. Introduction
2. Tecnologies Used
3. Application Creation Process
4. Setting up the Database and Server
5. Front End Development
6. Front End and Back End Connection
7. Recap and Conclusion  

Introduction - 
This project is a sample application built using the MERN stack, designed to demonstrate the implementation of CRUD operations in a full-stack environment. The application leverages MongoDB for the database, Express for the server framework, React for the front end, and Node.js for server-side logic. Additionally, Mongoose is used for MongoDB object modeling, and EJS templates are employed for certain server-side rendered views.

Technologies Used - 
MongoDB (M): NoSQL database used for storing application data.
Express (E): Web framework for Node.js, handling server-side logic and routing.
React (R): JavaScript library for building user interfaces.
Node.js (N): JavaScript runtime for executing server-side code.
Sequel: Used in some backend management aspects.
EJS (Embedded JavaScript Templates): Used for server-side rendering of HTML pages.
Mongoose: ODM (Object Data Modeling) library for MongoDB.
Bootstrap: CSS framework for responsive and modern web design.
Axios: Promise-based HTTP client for making API requests.
Postman: Tool for testing API endpoints.

Application Creation Process - 

This will include following 3 steps -

1. Setting Up the Database and Server -

Create a folder – mern/frontend and mern/backend
Go to mern/frontend and start your react app
![image](https://github.com/shwetak28/MERN-Application/assets/139232353/5e3deceb-8145-439f-a694-3bcc72e743e2)

Using Mongoose for MongoDB:
First install MongoDB community edition to your program files
Second Extra MongoDB shell to your C:// drive
Now set environment variable for both –

![image-1](https://github.com/shwetak28/MERN-Application/assets/139232353/5db516dc-52b0-4b96-a535-96af929a9dd7)

Mongoose is utilized to define the schema and model for the database.
Models and schemas are created to manage data efficiently.

Configuring the Server:
The server is set up using Node.js and Express.
Error management and response handling are implemented to ensure robust server operation.
And now restart your pc and go to cmd and type : mongosh

![image-2-768x370](https://github.com/shwetak28/MERN-Application/assets/139232353/70f4de2f-579c-47ef-aaa8-9ce21af86538)

2.Front End Development -
First go to the folder – mern/frontend and type : npm start

![image 3](https://github.com/shwetak28/MERN-Application/assets/139232353/c5bd0496-2e31-45a9-a534-ad1d89cf5deb)

Using the Bootstrap CSS Framework:
Bootstrap is integrated to create responsive and aesthetically pleasing forms and UI components.

Create, Read, Update, and Delete Forms:
Forms are created to handle CRUD operations, allowing users to interact with the application data.

Setup of Routing and Navigation:
React Router is used to manage application routes and navigation.
Redirects and routes are configured to provide a seamless user experience.

3. Front End and Back End Connection -
API Calls via Axios:
Axios is used to handle HTTP requests between the front end and back end.
API calls are made to perform create, read, update, and delete operations.
UAM Processing:
User Authentication and Management (UAM) are implemented for secure access and data management.
Postman Testing:
Postman is used to test API endpoints and ensure correct functionality.
Update and Delete Operations:
Data prefill and editing features are added to allow users to update existing records.
Predefined responses are set up to provide feedback to users.

Recap and Conclusion - 

This sample MERN stack application demonstrates the following key features:
- Full implementation of CRUD operations.
- Real-time error handling and response management.
- User-friendly interface with responsive design using Bootstrap.
- Robust front-end and back-end integration using Axios and React Router.
- Secure data management and user authentication.

By following the steps and techniques outlined in this project, you can gain a solid understanding of building full-stack applications using the MERN stack. This application serves as a foundation for creating more complex and feature-rich web applications in the future.

Thank you for exploring this sample MERN stack application! If you have any questions or suggestions, feel free to open an issue or submit a pull request.

Happy coding! 😊
