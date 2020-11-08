# Symfony-Todo-App
Simple CRUD app made with Symfony PHP Framework.
### Dashboard
![Todo Dashboard](./images/todo1.png)
### Create
![Todo Create](./images/todo2.png)
### Dashboard with todo items
![Todo with Items](./images/todo3.png)

## Requirements
* PHP >7.0 != 7.4 (7.4 has errors with Symfony)
* Symfony Framework
* Composer
* MySql database

## Usage
1. `git clone https://github.com/jcrucesdeveloper/Symfony-Todo-App.git`
1. Set up your MySQL database
  1. Start and MySQL database ( you can use the lampstack )
  1. Create an user, password and a database.
  1. Change the configuration file .env with your info (DATABASE_URL=mysql://YourUser:YourPassword@127.0.0.1:3306/YourDatabaseName?serverVersion=5.7)
1. Run `composer install` into the project folder 
1. Start your local server, in your project folder run `php bin/console server:run`
1. Try it!


