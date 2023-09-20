# NovelTea-Library

A simple Library with CRUD operations, made with the MERN Stack. It wasnt like any other planned project and I just went on adding basic features. Works as a library tho. And I loved using MongoDB.

# Screenshots

## Demo

![](/screenshots/demo.gif)

## Home Page

![](/screenshots/home.png)

## Add Book

![](/screenshots/add.png)

## Edit Book

![](/screenshots/update.png)

## Delete Book

![](/screenshots/delete.png)

## Search

![](/screenshots/search.png)

# Features

1. Add Books
2. Edit Books
3. Delete Books
4. Search Books

# How to run

You would have to start the server, and have mongo db installed to run the backend. For the Front end, you can visit the [The Deployed Website](https://noveltea.surge.sh/) or run it locally.

# Project Structure

The project has the following file structure:

```
bookstore
├── backend
│   ├── controllers
│   │   └── books.js
│   ├── models
│   │   └── Book.js
│   ├── routes
│   │   └── api.js
│   ├── app.js
│   ├── package.json
│   └── README.md
├── frontend
├── README.md
├── package-lock.json
├── package.json
├── public
│   ├── android-chrome-192x192.png
│   ├── android-chrome-512x512.png
│   ├── apple-touch-icon.png
│   ├── browserconfig.xml
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon.ico
│   ├── icon.png
│   ├── index.html
│   ├── manifest.json
│   ├── mstile-150x150.png
│   ├── robots.txt
│   ├── safari-pinned-tab.svg
│   └── site.webmanifest
├── src
│   ├── App.js
│   ├── components
│   │   ├── NavbarWithSearch.js
│   │   └── ui
│   │       ├── Book.css
│   │       ├── Book.js
│   │       ├── Rupee.js
│   │       └── SolarTeaCupBoldDuotone.js
│   ├── context
│   │   ├── BaseUrlContext.js
│   │   └── SearchResults.js
│   ├── index.js
│   ├── input.css
│   ├── pages
│   │   ├── AddBooks.js
│   │   ├── DeleteBooks.js
│   │   ├── Home.js
│   │   ├── SearchResult.js
│   │   └── UpdateBooks.js
│   └── style.css
└── tailwind.config.js
└── README.md
```

The `backend` directory contains the backend application, which consists of the `controllers`, `models`, and `routes` directories, as well as the `app.js` file, `package.json` file, and `README.md` file.

The `frontend` directory contains the frontend application, which consists of the `index.html`, `main.js`, and `style.css` files, as well as the `package.json` file and `README.md` file.

The root directory contains the main `README.md` file for the project.

## Backend

The backend application is built with Node.js and Express, and uses MongoDB as the database.

### Controllers

The `controllers/books.js` file exports a class `BooksController` which has methods to handle CRUD operations for books. It uses the `Book` model to interact with the database.

### Models

The `models/Book.js` file exports a class `Book` which represents a book in the database. It uses the `mongoose` library to define the schema and model for the book.

### Routes

The `routes/api.js` file exports a function `setApiRoutes` which sets up the API routes for the application. It uses the `BooksController` to handle the routes for books.

### App

The `app.js` file is the entry point of the backend application. It creates an instance of the express app, sets up middleware, and sets up the API routes.

### Package.json

The `package.json` file is the configuration file for npm. It lists the dependencies and scripts for the backend application.

### README.md

The `README.md` file contains the documentation for the backend application.

## Frontend

The frontend application is built with HTML, CSS, and JavaScript.

### Index.html

The `index.html` file is the HTML file for the frontend application. It contains a form to add a book and a table to display the list of books.

### Main.js

The `main.js` file is the JavaScript file for the frontend application. It contains functions to handle form submission and to fetch and display the list of books.

### Style.css

The `style.css` file is the CSS file for the frontend application. It contains styles for the HTML elements in the application.

### Package.json

The `package.json` file is the configuration file for npm. It lists the dependencies and scripts for the frontend application.

### README.md

The `README.md` file contains the documentation for the frontend application.

## Conclusion

This project is a simple example of a book store application built with Node.js, Express, and MongoDB on the backend, and HTML, CSS, and JavaScript on the frontend.

# Libraries used

1. [Express](https://expressjs.com/)
2. [Mongoose](https://mongoosejs.com/)
3. [React](https://reactjs.org/)
4. [Node](https://nodejs.org/en/)
5. [MongoDB](https://www.mongodb.com/)
6. [Tailwind CSS](https://tailwindcss.com/)
7. [React Router](https://reactrouter.com/)
8. [Heroicons](https://heroicons.com/)
9. [Material Tailwind](https://material-tailwind.com/)

# Credits

Thanks to Parents, Teachers and Friends for helping me out, as always...
