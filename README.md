# QuickJournal Readme

## Description
QuickJournal is a simple blogging application allowing users to maintain an individual blog online using a simple interface.

## Demo
Demo of QuickJournal will be available on Heroku (Heroku Link to add)

## Technologies
QuickJournal is constructed using MERN stack.
It uses React, React-Bootstrap for frontend and styling.
Mongoose, Express and Node compose the server architecture of this project.
Cors and axios are also used as middleware.
Database from MongoDB Atlas

## Technical Information
### Front End
Remember to install all dependencies with npm install or npx (bootstrap, react, etc)
Ensure that your connection string or Mongo ID is correct if working with development or local build.
### Back End
Ensure that all dependencies are installed using npm (mongoose, express, cors)
run with npm start 'server.js' or nodemon 'server.js'. 
Remember to add your connection string to ensure DB access on back end.
### Contribute to QuickJournal
QuickJournal is not currently accepting  additional contribution or collaboration, however, any comments or feature requests can be sent through GitHub messages or by email.

## Issues
### Upcoming Features
Friends List
Separation into multiple blogs-- Visit other pages and leave comments
Favorite Blog/User
Recent Blog Carousel
Private/Public toggle on blogposts
Image/Sound/Video posts in addition to text posts
Tag system improvement

## API ENDPOINTS
GET api/posts Get all Blogposts 
GET ''/posts/:id Get single post by id
POST ''/posts Create new post
PUT ''/posts/:id Update post
DELETE ''/posts/:id Delete post by id
