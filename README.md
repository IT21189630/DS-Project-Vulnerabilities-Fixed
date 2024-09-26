# Learnup Web Application - Vulnerabilities Fixed

This repository contains the version after fixing the vulnerabilities of the Learnup web application. Please follow the steps given down below to setup the application and run it.


## Steps to setup the application.
step 1 -> Clone the repository
step 2 -> Go to every directory in the project and run the command **npm install**
step 3 -> After all the necessary libraries installed, go to every directory and run the command **npm start** to bring every service online.

## Steps to setup Google Auth.
step 1 -> Go to google developer console and setup a new project.
step 2 -> Copy the **client_id** and **client_secret** from your google app.
step 3 -> Go to the **service-user-management** directory of the project and find the **.env** file.
step 4 -> Add your copied client_id and client_secret as 2 environment variables.

CLIENT_ID  = your_client_id
CLIENT_SECRET  = your_client_secret 


