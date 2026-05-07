# MIU-CS472-2026-04-NodeJS-Workshop
# Given the following structure
User {
  id: string;//unique
  name: string;
  email: string;
}
# Complete the following tasks
1. Initialize your NodeJS from scratch
2. Create the interface User (user.ts) with the above structure
3. Create the server using express in app.ts with the following routes
* POST /users : Create a new user and return this user. The user ID should be generated automatically. You may use UUID to create ID at `https://www.npmjs.com/package/uuid`
* GET /users: Return all users
* DELETE /users/:id: Delete a user if it exist and return the remaining users. Throw an error if it does not exist
4. Add error handler for this app
# Create user in memory to test
# Complete at 1:30 PM 
