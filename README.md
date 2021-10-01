# Interview-deqode

# Web Development API Task

**Your task is to create an API's to manage CRUD (Create, Read, Update and Delete) Operations.**

We would expect this task to take one hour in order to complete REST API's. Please find a few pointers below:

Your solution _must_:

- Be implemented with Node.js.

- Expose a user model, with (at least) the following attributes:
  - **`id`** - _a unique user id_
  - **`name`** - _in the UK this is the user's last name_
  - **`email`** - _a user's email address_
  - **`password`** - _it should be increpted password_
  - **`created_at`** - _the date and time the user was added_
  - **`updated_at`** - _the date and time the user was updated_

- You can choose any database (MongoDB, PostGres, MySQL)
- You can use any framework of node js (express, loopback, nest)
- Setup directory structure with MVC pattern (Or based on Clean architecture)
- Password should be encrypted by bcrypt or custom logic
- Must have validations like minimum length and maximum length, empty checks and valid email
- It should contain services, constants, helper function files
- It should contain .env file to get PORT,SECRET and other environment variables
- Try to use validation library like JOI or express validator
- Optional (You can implement sessions as well if you want)

