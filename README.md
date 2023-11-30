# Sociopedia
Developed a full-stack web application based project on social media application. Its' completely responsive and uses MongoDB Express React and NodeJs (MERN) as the core tech-stack.

# Featurs included in this project
## project features:
• user authentication: implement a secure login/logout system.

• mongoDB integration: use MongoDB for data storage. Demonstrate how to perform CRUD (Create, Read, Update, Delete) operations.

• api development: create RESTful APIs for the following functionalities:

* user profile management: allow users to create, view, and edit their profiles.

* post creation and retrieval: enable users to create posts and retrieve them.

* commenting system: users should be able to comment on posts.

• error handling: implement comprehensive error handling and logging.

• documentation: provide clear documentation on the setup and usage of your backend.

## user features:
• register and login users.

• post images can be uploaded using file system.

• pagination on every pages.

• Dark mode.

• copy link of post.

• search other users by username.

• make friends with other users.

• delete posts and comments.

• Explore page to view other posts by random users.

• profile page.

• edit profile page user data.

• password is stored in database in encrypted format with salt.

• create and edit posts.

• like ,comment, share and edit posts.

• posts include text(caption) and image(s).

• comment on posts.

• reply comments.

• like commets.

• profile page shows user details and posts with following and followers menu.

# Getting started

## Clone the repository
```
https://github.com/Brothin/Sociopedia.git
```
```
cd Sociopedia
```

## You need
• Node

• MongoDB or Mongo Atlas

• NPM

## Create your MongoDB account and database/cluster
• Create your own MongoDB account by visiting the MongoDB website and signing up for a new account.

• Create a new database or cluster by following the instructions provided in the MongoDB documentation. Remember to note down the "Connect to your application URI" for the database, as you will need it later. Also, make sure to change with your own password.

• Add your current IP address to the MongoDB database's IP whitelist to allow connections (this is needed whenever your ip changes).

## Create .env file
Create a .env file in the server folder to store your credentials. This file will store environment variables for the project to run. I have already added example.env for your reference.
```
MONGO_URL = 'mongodb+srv://<username>:<password>@mongodburlhere'
JWT_SECRET = 'somesuperhardstringtoguess'
PORT = 3001
```

## Installation
To install and run this project - install dependencies using npm in root folder.
```
npm install
npm i nodemon
```
Install dependencies using npm in client folder and run client side of application.
```
cd client
npm install
npm start
```
Install dependencies using npm in server folder and run server side of application.
```
cd server
npm install
npm start
```
