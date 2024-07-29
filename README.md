# CodeAlpha_Personal-Library
## Overview
Personal Library is a web application that allows users to manage a collection of books. It provides features to add, edit, view, and delete books, along with a search functionality to easily find books in the collection.

## Features
- Search Books: Search for books by title.
- View Books: View a list of all books in the collection and filter them by availability.
- Add Book: Add new books to the collection with details like title, author, ISBN, genre, tags, and description.
- Edit Book: Edit the details of existing books.
- Delete Book: Remove books from the collection.
- Borrowed Books: View a list of borrowed books.

## Tech Stack
- Frontend:
  - React with React Router for navigation
  - Tailwind CSS for styling
- Backend:
  - Node.js with Express for the server
  - MongoDB with Mongoose for database management

## Getting Started
### Prerequisites
- Node.js
- MongoDB

### Installation
1. Clone Repo
```bash
https://github.com/ShibuSingh2k01/CodeAlpha_Personal-Library.git
cd personal-library
```

2. Install Dependencies
```npm install```
Note - Make Sure to do this for Backend Folder too
3. Ensure MongoDB is installed and running on your local machine. The default configuration uses a local MongoDB instance at mongodb://localhost:27017/library.
4. Start the Server
```
npm run dev
```
5. Start the Frontend
```
npm run dev
```

## Usage
- Home Page: View all books in the library.
- Add Book: Click on "Add Book" to add a new book.
- Edit Book: Click on a book title and then on "Edit Book" to modify its details.
- Delete Book: Click on a book title and then on "Delete Book" to remove it from the collection.
- Search: Use the search bar to find books by title.
