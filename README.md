# Library Management System – Advanced Java OOP Assignment

## Project Overview

This **Library Management System** is a console-based Java application developed to demonstrate practical usage of **Object-Oriented Programming (OOP)** principles, including:

- Abstraction
- Encapsulation
- Inheritance
- Polymorphism
- Interfaces
- Exception Handling
- Modularity
- Simulated persistence and concurrency



##  Technologies Used

- Java 17+
- Java Collections Framework
- Java Time API (`LocalDate`, `ChronoUnit`)
- UUID for unique identification
- ConcurrentHashMap for thread-safe collections



##  Key Classes & Responsibilities

###  `Book`
- Represents each book with details like title, author, genre, issue status, and reservation queue.

###  `Member` *(Abstract)*
- Common base class for all users.
- Subclasses:
  - `StudentMember`: Can borrow 3 books for 14 days.
  - `TeacherMember`: Can borrow 5 books for 30 days.
  - `GuestMember`: Can borrow 1 book for 7 days.

###  `Librarian`
- Can add/remove books, register members, and view overdue books.

###  `LibrarySystem`
- Handles core operations: issue/return/reserve/search books, register members, manage catalog.





