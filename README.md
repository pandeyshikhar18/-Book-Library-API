# 📚 Book Library API

This project demonstrates a custom API server for managing a library of books using Node.js, Express, and MongoDB.

## 🚀 Features
- 4 CRUD API Endpoints
- MongoDB Database
- Optional HTML + JS frontend
- Curl/Postman Testing

## 📦 Tech Stack
- Node.js
- Express.js
- MongoDB + Mongoose
- (Optional) HTML + JS

## 📡 API Endpoints

| Method | Endpoint            | Description       |
|--------|---------------------|-------------------|
| POST   | `/api/books`        | Add a book        |
| GET    | `/api/books`        | List all books    |
| PUT    | `/api/books/:id`    | Update a book     |
| DELETE | `/api/books/:id`    | Delete a book     |

## 🔧 Running Locally

```bash
git clone https://github.com/your-username/book-library-api.git
cd backend
npm install
touch .env
# Add MONGO_URI to .env
npm start
