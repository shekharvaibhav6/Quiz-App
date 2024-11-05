Full-Stack Quiz Management System

An end-to-end quiz management system with a responsive frontend and a robust backend, leveraging Java Spring Boot, JPA, and a relational database to auto-generate schemas based on defined entities. This project demonstrates the seamless integration of frontend and backend components for efficient data management and interactive user experiences.

🚀 Features

Backend: Built with Java Spring Boot and JPA, providing an API to handle quiz data, questions, options, and correct answers without manually writing SQL. The schema is generated automatically through JPA entities.
Frontend: Fully responsive interface, delivering an intuitive experience for creating, viewing, and managing quizzes.
Database: Automatically generated relational database structure that manages questions and their corresponding answer options.
🛠️ Technologies Used

Backend: Java, Spring Boot, JPA (Java Persistence API)
Frontend: HTML, CSS, JavaScript
Database: MySQL

Prerequisites
Java 21
MySQL
Maven

📊 Database Schema

The database schema is automatically generated by JPA based on entity classes in the backend. Key tables include:

Quiz Question: Stores quiz questions with text and the correct answer.
Question Options: Stores multiple options for each quiz question.