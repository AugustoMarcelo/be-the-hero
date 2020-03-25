# Application developed in the 11th Omnistack Week

**Be The Hero** is an application that allows to manage ONGs and the incidents registered by them. The goal is to allow anyone to help them.

## Technologies used
 - express
 - <a href="http://knexjs.org/">knex</a>
 - sqlite3

## Instructions for running the backend
- After cloning the repository, enter the *backend* folder and run the `yarn` command. It is a package manager that will download the project's dependencies.

- After downloading all the dependencies, still inside the *backend* folder, execute the command `yarn ml`. This command is a shortcut to `yarn knex migrate: latest`, which will perform the migrations responsible for creating the tables in the database.

- With the tables created, run `yarn start` to boot the server.

## Screens (WEB)
> Logon Page
<img href="./screens/logon.png" alt="Logon Page">

> Register Page
<img href="./screens/register.png" alt="Register Page">

> Profile Page (Incidents List)
<img href="./screens/profile.png" alt="Profile Page">

> New Incident Page
<img href="./screens/new-incident.png" alt="New Incidente Page">