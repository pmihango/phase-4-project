# Best Books | A Book Club App

This app lets you create book clubs with your friends where you can track goals, create discussion questions, and comment on the discussion questions.

## Back-end Best Books Interface
You can use this app in conjunction with my book club app API [see the repo](https://github.com/AbelRutto/backend-api-for-best-books)

## Technologies Used In This App

- JavaScript
- React
- Mui
- React Router
- Goodreads API

## How To Use

Install and run:

```sh
npm install
# start up your server
# start up react
npm start

```
## setting up the project 
Setup to use port 4000  in running the front-end and use an API on port `http://127.0.0.1:3000/` in running back-end

## Features

### App

- customize theme with Mui
- ability to add users and login
- persistent login using cookies
- ability to update user information and icon color
- ability to delete your own profile
- responsive design

### Book Clubs

- Create a book club
- Edit a book clubs info and users if you are the admin
- Delete a book club
- View all book clubs you are a part of
- View book club archived books, wishlist books, and currently reading book

### Books

- Search for books using the Goodreads API
- Search popular lists of books using the Goodreads API
- View books images, author, description, and genres
- Select a book and add it to a book clubs wishlist
- Move the book to wishlist, archived books, or currently reading

### Currently Reading

- Search for books using the Goodreads API
- Comment on guide questions if you are a part of the book club
- If you are an admin you can:
  - Edit the current books progress
  - Move book to completed and archived books
  - Create, edit, and delete goals
  - Create, edit, and delete guide questions
  - Create, edit, and delete all comments left
