<img src="https://i.ibb.co/4j97Gj5/Task-1.png" alt="Task" />

# TaskX 

TaskX is a to-do list that incorporates a program as well as the api for it. This API is built in NodeJS/Express, along with various dependencies to make the building of the application quicker and seamless.

*Insert link for application*

## License Information

This is a public code repository, and can be used however anyone wants to. I only ask if you use it in it's entirety to leave a link back to this repository.

## Purpose

This is used as the back-end of the TaskX application. This API handles the users and tasks stored.

## Features

 - Sign-up / Log-in
 - Password Reset
 - Task Management (CRUD)
 - CRON database cleanup (Daily at midnight)

## Endpoints

### /users
 - POST: Creates a new user
 - PATCH: Updates a user
 - DELETE: Deletes a user
 - GET: Gets information regarding a user

### /tasks
 - POST: Creates a new task
 - PATCH: Updates a task
 - DELETE: Deletes a task
 - GET: Gets informations regarding a task

## Database Schema

### Users
 - id
 - public_id
 - email
 - password
 - active

### Tasks
 - id
 - public_id
 - task_name
 - description
 - date_created
 - date_completed