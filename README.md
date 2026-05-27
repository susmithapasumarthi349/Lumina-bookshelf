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

## 🏗 System Architecture ##⚙ How to Run

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


📌 REST API Endpoints

| Method | Endpoint   | Function                |
| ------ | ---------- | ----------------------- |
| GET    | /books     | Retrieve all books      |
| POST   | /books     | Add a new book          |
| PUT    | /books?id= | Update reading progress |
| DELETE | /books?id= | Delete a book           |


##⚙ How to Run
Compile Java files:
javac *.java

Run server:
java BookServer

Open browser:
http://localhost:5500


##🔮 Future Enhancements
Database integration
Authentication system
Cloud deployment
AI book recommendations
Reading analytics
Mobile application

👩‍💻 Author

Susmitha Pasumarthi
