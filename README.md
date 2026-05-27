# 📚 Lumina Bookshelf

A Personal Reading Tracker and Book Management System developed using Java, HTML, CSS, and JavaScript. The application allows users to manage books, track reading progress, search and filter records, and monitor reading statistics through an interactive dashboard.

---

## 🚀 Features

- Add books to personal library
- Update reading progress
- Delete books
- Search books by title or author
- Filter books by status:
  - Reading
  - Completed
  - Unread
- Dashboard statistics
- Progress bars
- Persistent file storage
- Dynamic frontend updates

---

## 🛠 Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Java
- Java HttpServer

### Data Structure Used
- ArrayList<Book>

### Storage
- books.txt

### Concepts Implemented
- Object-Oriented Programming
- REST APIs
- CRUD Operations
- File Handling
- Data Structures

---

## 🏗 System Architecture

```text
User Interface
      ↓
JavaScript Fetch API
      ↓
Java HTTP Server
      ↓
BookService
      ↓
ArrayList<Book>
      ↓
books.txt
```

---

## 📌 REST API Endpoints

| Method | Endpoint | Function |
|----------|----------|----------|
| GET | /books | Retrieve all books |
| POST | /books | Add a new book |
| PUT | /books?id= | Update reading progress |
| DELETE | /books?id= | Delete a book |

---

## ⚙ How to Run

### Step 1: Compile Java Files

```bash
javac *.java
```

### Step 2: Run Server

```bash
java BookServer
```

### Step 3: Open Browser

```text
http://localhost:5500
```

---

## 📋 Functional Workflow

1. User enters book details  
2. Book is stored in ArrayList<Book>  
3. Data is saved into books.txt  
4. Library dashboard displays books  
5. User can search/filter books  
6. Progress can be updated  
7. Books can be deleted  

---

## 📚 Learning Outcomes

- Implemented CRUD operations
- Worked with REST APIs
- Applied Data Structures using ArrayList
- Learned File Handling
- Integrated frontend and backend
- Built Java HTTP server
- Understood client-server architecture

---

## 🔮 Future Enhancements

- Database integration (MySQL/PostgreSQL)
- Authentication system
- Cloud deployment
- AI book recommendations
- Reading analytics
- Mobile application

---

## 👩‍💻 Author

Susmitha Pasumarthi
