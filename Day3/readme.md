# 📚 Books API

A simple ASP.NET Core Web API for managing book records. This project is designed using a clean architecture approach, separating concerns across **Data**, **Services**, and **Web API** layers.

---

## 🧩 Project Structure

```
BooksApi/
├── BooksApi.sln                  # Solution file
├── BooksApi/                     # ASP.NET Core Web API project
│   ├── Controllers/              # API controllers (e.g., BookController)
│   ├── Program.cs                # Entry point of the Web API
│   ├── appsettings.json          # Configuration settings
│   ├── Properties/
│   └── ...
├── BooksApi.Data/                # Data models and access layer
│   └── Models/Book.cs            # Book data model
├── BooksApi.Services/           # Business logic layer
    └── Services/BookService.cs   # Service to manage book operations
```

---

## 🚀 Features

- 📖 Get a list of books  
- ➕ Add a new book  
- ✏️ Update existing book details  
- ❌ Delete a book  
- Follows a layered architecture for maintainability and testability

---

## ⚙️ Tech Stack

- .NET 8.0  
- ASP.NET Core Web API  
- C#  
- RESTful API design

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/BooksApi.git
cd BooksApi/BooksApi
```

### 2. Build the Solution

Make sure you have the .NET SDK installed. Then run:

```bash
dotnet build
```

### 3. Run the Application

```bash
dotnet run
```

The API will be hosted at: `https://localhost:5001` or `http://localhost:5000`

---

## 📬 API Endpoints

| Method | Endpoint             | Description         |
|--------|----------------------|---------------------|
| GET    | /api/book            | Get all books       |
| POST   | /api/book            | Add a new book      |
| PUT    | /api/book/{id}       | Update book by ID   |
| DELETE | /api/book/{id}       | Delete book by ID   |
