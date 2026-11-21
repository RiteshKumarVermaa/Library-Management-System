# Library Management System

A Spring Boot based Library Management REST API developed using Java to manage book records efficiently.

## Features

- Add new books
- Retrieve all books
- Retrieve a specific book by ID
- Update book details
- Delete books by ID
- Return appropriate HTTP responses

## Technologies Used

- Java
- Spring Boot
- Spring Web
- Maven
- REST API

## Project Structure

```text
librarymanagement/
├── src/
│   ├── main/
│   │   ├── java/com/library/librarymanagement/
│   │   │   ├── Book.java
│   │   │   ├── BookController.java
│   │   │   └── LibrarymanagementApplication.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
├── pom.xml
└── README.md
```

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/books` | Add a new book |
| GET | `/books` | Get all books |
| GET | `/books/{id}` | Get book by ID |
| PUT | `/books/{id}` | Update book details |
| DELETE | `/books/{id}` | Delete a book |

## Book Fields

- id – Integer
- title – String
- author – String
- category – String
- availableCopies – Integer

## How to Run

1. Install Java.
2. Open the project in VS Code.
3. Open the terminal in the project folder.
4. Run the following command:

```bash
.\mvnw.cmd spring-boot:run
```

5. Open the API in your browser:

```text
http://localhost:8080/books
```

## Author

Ritesh Kumar Verma