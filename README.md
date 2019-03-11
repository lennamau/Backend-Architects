# Worther Backend

A Backend for Worther App

### Local Use

- run `yarn` in order to install all dependencies
- use the command `yarn server` to run nodemon live server


## Endpoints

### Users Overview


| Method |     Endpoint     |                  Requires                    |                                        Description                            |
|--------|------------------|----------------------------------------------|-------------------------------------------------------------------------------|
|  POST  | `/api/register` | `username`, `email`, `password`| Used for adding a new user .                                       |
|  POST  | `/api/login`    |  `username`, `password`| Login with username and password. Provides JWT to user    |
|  GET   | `/api/users`     |  Successful Login  | Shows a list of users if logged in.                 