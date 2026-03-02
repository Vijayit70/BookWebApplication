📚 BookWeb Application

A simple Book Management Web Application developed using Java Servlets, HTML, and Bootstrap that performs full CRUD (Create, Read, Update, Delete) operations.

This project demonstrates basic Java Web Development concepts including Servlets, request handling, database interaction, and frontend UI integration.

🚀 Project Overview

The BookWeb Application allows users to manage book records through a web interface. Users can:

➕ Add new books

📖 View book list

✏️ Edit book details

❌ Delete books

The application follows a simple MVC-like structure using Java Servlets as controllers.

🛠️ Technologies Used

Java (Servlets & JSP concept)

HTML5

Bootstrap

JDBC

MySQL Database

Apache Tomcat Server

📂 Project Structure
BookWebApplication/
│
├── src/
│   ├── BookListServlet.java
│   ├── RegisterServlet.java
│   ├── DeleteServlet.java
│   ├── EditScreenServlet.java
│
├── WebContent/
│   ├── home.html
│   ├── register.jsp (or html form)
│   ├── bootstrap files
│   └── 
│
├── WEB-INF/
│   └── web.xml
│
└── README.md
⚙️ Features

✅ Add new book records
✅ Display all books in table format
✅ Update book name and price
✅ Delete existing records
✅ Responsive UI using Bootstrap
✅ Simple and beginner-friendly architecture

📑 Servlets Description
1️⃣ BookListServlet.java

Displays all books stored in the database.

Fetches records using JDBC.

Shows data in table format.

2️⃣ RegisterServlet.java

Handles insertion of new book records.

Accepts form data from user.

Saves book details into database.

3️⃣ DeleteServlet.java

Deletes a selected book entry.

Uses book ID to remove records.

4️⃣ EditScreenServlet.java

Loads selected book details.

Allows user to modify book name and price.

Updates database record.

5️⃣ home.html

Landing page of the application.

Provides navigation to book operations.

🗄️ Database Configuration
Sample Table Structure
CREATE TABLE books (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    price DOUBLE
);
🔧 Setup & Installation

Follow these steps to run the project locally:

1️⃣ Clone Repository
git clone https://github.com/Vijayit70/BookWebApplication.git
2️⃣ Import Project

Open Eclipse / IntelliJ IDEA

Import as Dynamic Web Project

3️⃣ Configure Apache Tomcat

Install Apache Tomcat

Add server in IDE

Deploy project on Tomcat

4️⃣ Setup Database

Create MySQL database

Run table creation query

Update JDBC credentials in servlet files

String url = "jdbc:mysql://localhost:3306/bookdb";
String username = "root";
String password = "yourpassword";
5️⃣ Run Application

Start Tomcat Server and open:

http://localhost:8080/BookWebApplication

📸 Screenshots 

You can add screenshots here:

<img width="1422" height="575" alt="editscreen" src="https://github.com/user-attachments/assets/81035d4b-09ea-478a-a2be-534466e3c1d9" />
Home Page
<img width="1691" height="727" alt="home" src="https://github.com/user-attachments/assets/1e73b21f-c23a-4b99-8edf-019c14cc8b53" />
Book List Page
<img width="1517" height="734" alt="booklist" src="https://github.com/user-attachments/assets/d390696c-163d-4b0c-8f67-5c7e5069ec3c" />
<img width="1506" height="758" alt="booklist1" src="https://github.com/user-attachments/assets/bed8295b-af6d-4013-9201-c088c35beda4" />

Add Book Form
Edit Book Screen
🎯 Learning Outcomes

Understanding Java Servlets lifecycle

Handling HTTP Requests & Responses

JDBC database connectivity

CRUD operations implementation

MVC basics in Java Web Applications

Bootstrap UI integration

👨‍💻 Author

Vijay Tiwari
B.Tech IT Student | Java & Web Development Learner

📄 License

This project is created for learning and educational purposes.

⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork it
📢 Share with others
