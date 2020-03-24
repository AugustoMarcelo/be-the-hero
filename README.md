# Application developed in the 11th Omnistack Week

**Be The Hero** is an application that allows to manage ONGs and the incidents registered by them. The goal is to allow anyone to help them.

## Technologies used
 - express
 - knex
 - sqlite3

## Instructions for running the backend
After cloning the repository, enter the *backend* folder and run the `yarn` command. It is a package manager that will download the project's dependencies.

After downloading all the dependencies, still inside the *backend* folder, execute the command `yarn ml`. This command is a shortcut to `yarn knex migrate: latest`, which will perform the migrations responsible for creating the tables in the database.

With the tables created, run `yarn start` to boot the server.