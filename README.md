# Restful.Api
# User Management RESTful API

## Overview
This project is a RESTful API built with Node.js and Express. It allows users to:
- View all users.
- Find users by ID.
- Find users by profession.
- Find users by name.

## Endpoints
1. **Get All Users**
   - Route: `/users`
   - **Screenshot:**  
     ![All Users](./Screenshot_postman/users_list.png)

2. **Get User by ID**
   - Route: `/users/:id`
   - **Screenshot:**  
     ![User by ID](./Screenshot_postman/specific_user.png)

3. **Get Users by Profession**
   - Route: `/users/profession/:profession`
   - **Screenshot:**  
     ![Users by Profession](./Screenshot_postman/profession.png)

4. **Get User by Name**
   - Route: `/users/name/:name`
   - **Screenshot:**  
     ![User by Name](./Screenshot_postman/name.png)

## What I Learned
- Building a RESTful API with multiple endpoints.
- Handling file operations using the fs module.
- Testing APIs using Postman.
- Implementing error handling for invalid inputs.

## Testing
Screenshots of the testing process are included to show the API's responses and functionality.

## Discussion
This project helped me understand the basics of API development and testing. Testing with Postman was especially useful for debugging and verifying the API’s outputs.

