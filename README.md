# Book CRUD API
A simple REST API built with **Node.js** and **Express** that allows you to perform **Create**, **Read**, **Update**, and **Delete** (CRUD) operations on a collection of books stored in memory (no database used).

## Features
- In-memory storage (no DB setup required)
- Basic CRUD operations:
- 'GET /books' – List all books
- 'POST /books – Add a new book
- 'PUT /books/:id' – Update an existing book
- 'DELETE /books/:id' – Delete a book

## Requirements
- [Node.js](https://nodejs.org/) installed

## How to Run

1. **Clone the repo**
   git clone https://github.com/saisri2501/books-api-crud.git
   cd book-api-crud
2. **Install dependencies**
    npm install
3. **Start the server**
   node index.js
4. **API will be running at:**
   http://localhost:3000
   
**API Endpoints:**
GET /books:
Returns a list of all books.

POST /books:
Adds a new book.
Body (JSON):

{
  "title": "Book Title",
  "author": "Author Name"
}

PUT /books/:id
Updates a book by ID.
Body (JSON):

{
  "title": "Updated Title",
  "author": "Updated Author"
}

DELETE /books/:id
Deletes a book by ID.
