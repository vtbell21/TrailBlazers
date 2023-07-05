# TrailBlazers

TrailBlazers is a full-stack web application where users can leave reviews on hiking trails. Developed using JavaScript, HTML, CSS, Node.js, Express, and MongoDB, with full CRUD functionality that enables users to easily create, read, update, and delete their reviews.

## Features

- Authentication
  - User login with username and password
- Authorization
  - Users cannot manage posts and view user profile without being authenticated
  - Users cannot edit or delete posts and comments created by other users
  - Admin can manage all posts and comments
- Manage trail reviews with basic functionalities
  - Create, edit and delete posts and comments
  - Upload campground photos
  - Search existing trails
- Responsive web design
- Mangage user account with basic functionalities

## Installation
1. Install [mongodb](https://www.mongodb.com/)
2. Create a Cloudinary account to get an API key and secret code
   ```shell
   git clone https://github.com/vtbell21/TrailBlazers.git
   cd TrailBlazers
   npm install
    ```
3. Create a .env file in the root of the project and add:
    ```shell
    DATABASEURL='<url>'
    API_KEY=''<key>
    API_SECRET='<secret>'
    ```
4. Run `mongod` in another terminal and node app.js in the terminal with your project and go to 'http://localhost:3000'


