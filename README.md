# PDI Resources

This repository is a hands-on learning workspace containing multiple small applications, demos, and exercises built with Java, Spring Boot, .NET, and Node.js. The projects cover common enterprise patterns such as REST APIs, JPA persistence, security, payment processing, Razor Pages, authentication, MongoDB integrations, and modern frontend development.

The goal of this repo is to practice real-world application development in a compact, modular setup. Each project is meant to be run independently from its own folder.

## Repository Overview

This workspace includes:

- Spring Boot and Java projects for APIs, persistence, validation, and AOP
- ASP.NET Core applications for authentication, payment processing, and business apps
- Express.js and MongoDB-based backend services
- React and Next.js frontend examples
- Small console and utility programs used for Java and C# learning

## Technology Summary

- Java 21 / Spring Boot 3.x
- Spring Data JPA, validation, and AOP
- MySQL connectivity for backend examples
- ASP.NET Core / Razor Pages / Web API
- Entity Framework Core and MySQL
- JWT authentication and authorization
- Node.js / Express.js / Mongoose
- React + Vite frontend UI
- Next.js app starter project

---

## App-by-App Inventory

| App Folder | Stack | Purpose |
| --- | --- | --- |
| AddressbookApp | Java / Console App | Console-based address book exercise demonstrating contact storage, duplicate detection, and object-oriented Java design. |
| addressbook-jpa | Java / Spring Boot / JPA | Spring data JPA sample focused on persistence and CRUD operations for contacts. |
| addressbookv2 | Java / Spring Boot | Follow-up or revised version of the address book application with additional refinements. |
| AuthApp | ASP.NET Core | JWT-based authentication and authorization service for API security scenarios. |
| basicsecurity | Java / Spring Boot | Spring Security demo illustrating authentication and authorization basics. |
| ContactManager | C# / Console App | Simple console-based contact manager for learning C# fundamentals and data handling. |
| departmentsApp | Java / Spring Boot | Department management sample for learning REST APIs and service layer patterns. |
| ExampleLambda | Java | Java lambda expression example for functional programming basics. |
| ExampleMethodRef | Java | Method reference examples to practice Java 8+ functional coding techniques. |
| FileVsitor | Java | File processing or traversal demo for learning file system operations. |
| libraryManagementSystem | Java / Spring Boot | Library management project for books, loans, or membership-related workflows. |
| PaymentApp | ASP.NET Core | Minimal payment processing API that stores payment transactions and exposes endpoints for processing and retrieval. |
| TodoList | ASP.NET Core / Razor Pages | To-do application using Razor Pages and in-memory database storage. |
| VKKirana | ASP.NET Core | Grocery or commerce-related backend with products, customers, orders, and payment orchestration. |
| VKKiranav1 | ASP.NET Core | Earlier version of the VKKirana application using a similar e-commerce domain model. |
| consoleexample | C# / Console | Console-based authentication/secure input example demonstrating user input handling. |
| expressapp1 | Node.js / Express / MongoDB | Express API with property data and Mongoose integration. |
| expressapp2 | Node.js / Express / MongoDB | Expanded API version with property and user routes using MongoDB. |
| homeslistingapp | Node.js / Express / MongoDB | Property listing backend for a home or real-estate application. |
| homeslistingui1 | React + Vite | Frontend UI for property listing display and browsing interactions. |
| my-next-app1 | Next.js | Next.js starter project used to learn app routing and modern frontend patterns. |
| nodeapp_resources | Node.js | General Node.js reference and learning project for backend scripting examples. |
| scansum | Java / Console App | File-based scanner program that reads numeric values and calculates their total sum. |
| springAopDemo | Java / Spring Boot / AOP | Spring AOP learning app demonstrating cross-cutting concerns like logging and validation. |
| src | Mixed | General source folder for shared or exploratory code samples. |
| Capstone-references | Docs / References | Reference material and supporting resources for capstone or coursework work. |

---

## Detailed Project Notes

### Java Projects and Spring Boot Examples

#### AddressbookApp
A Java console application for managing contacts. It demonstrates object-oriented design, duplicate prevention, and simple in-memory address book operations in a beginner-friendly format.

#### addressbook-jpa
This is a JPA-focused address book example. It demonstrates how to map entities to a database, create repository patterns, and perform CRUD operations with Spring Data JPA. It is a practical example of persistence-driven Java development.

#### addressbookv2
A second iteration of the address book app, likely used to refine or expand earlier concepts such as validation, services, or model updates. It is useful as a comparison point against the original implementation.

#### basicsecurity
This project demonstrates Spring Security fundamentals, including authentication and authorization. It is a good example of securing application endpoints using Java-based backend practices.

#### departmentsApp
This app models department data and is useful for learning RESTful service layers, entity relationships, and path-based resource APIs in a Spring Boot project.

#### libraryManagementSystem
A library management sample with project naming that suggests book inventory, issue/return flows, and catalog management. It is a good example of a domain-focused CRUD application in Java.

#### springAopDemo
This project focuses on Aspect-Oriented Programming in Spring. It is used to demonstrate cross-cutting concerns like logging, transaction monitoring, or validation without directly modifying business code.

#### scansum
A Java console-based file reader that scans numeric values from a text file and calculates their sum. It is a practical example of file input, parsing, and basic Java stream control.

#### ExampleLambda and ExampleMethodRef
These are Java functional programming examples. They help practice lambda expressions and method references, which are common in modern Java streams and collection-based processing.

#### FileVsitor
This project is likely focused on file system traversal or file inspection logic. It is useful for understanding directory walking, file metadata, and recursive processing in Java.

### .NET / ASP.NET Core Projects

#### AuthApp
This is an ASP.NET Core Web API built around JWT token authentication. It configures database access, security settings, and controllers for protected endpoints. It is a strong example of secure API development in .NET.

#### PaymentApp
A payment processing API that accepts payment requests, validates input, stores transaction data, and returns a success or status response. It is a representative demo for backend transaction workflows and database-backed APIs.

#### TodoList
A Razor Pages application that stores TODO items in an in-memory database. It is a simple and practical example of ASP.NET Core UI development with page-based architecture.

#### VKKirana
This is a more complete business application built with ASP.NET Core. It includes products, customer orders, payment details, repositories, services, AutoMapper, and external HTTP integration, making it a multi-layer sample for real-world backend design.

#### VKKiranav1
This is an earlier version of the VKKirana solution, useful as a historical or comparison version while learning layered software design and API evolution.

#### ContactManager
A C# console application for managing contacts. It demonstrates simple data handling and command-line interaction in a .NET environment.

#### consoleexample
This is a small console sample showing secure username/password input handling and console-based interaction, often used to learn common C# fundamentals.

### Node.js / Express / Frontend Projects

#### expressapp1
A basic Express API connected to MongoDB using Mongoose. It exposes property-related routes and is designed to illustrate how backend APIs interact with a document database.

#### expressapp2
A more advanced Express service that includes property and user routes. It shows how a Node backend can be organized with multiple route files and MongoDB connectivity.

#### homeslistingapp
This is a property listing backend, likely intended for a real-estate or home-search use case. It demonstrates API design for listing and managing property data.

#### homeslistingui1
This React frontend consumes property listing data in a UI-oriented workflow. It is an example of a Vite-based React app using component-driven design.

#### my-next-app1
A Next.js starter application for learning modern React application architecture, page routing, component organization, and frontend tooling.

#### nodeapp_resources
A supporting Node.js project for learning generic backend concepts, scripts, and small utilities. It acts as a lightweight playground for JavaScript server-side experimentation.

---

## Suggested Usage

This repo is not a single app; it is a collection of practice projects. To work on one of them:

1. Open the project folder you want to run.
2. Use the framework-specific commands:
   - Java / Maven: mvn spring-boot:run
   - .NET: dotnet restore && dotnet run
   - Node.js: npm install && npm start
3. Check the project’s configuration files for environment-specific variables (for example, database connection strings or JWT secrets).

---

## Notes

- Many projects are educational and experimental rather than production-ready.
- Some folders are earlier/later versions of the same concept, useful for comparison.
- Database configuration may differ between projects, so connection strings and environment variables must be reviewed before running a project.
- This repository is best used as a training ground for backend, API, and full-stack fundamentals.

---

## Summary

The workspace is a rich collection of learning apps covering:

- CRUD and REST API design
- Persistence with JPA and Entity Framework
- Advanced Java and Spring concepts
- ASP.NET Core and Razor Pages
- Security and JWT integration
- Node.js and MongoDB backend services
- React and Next.js frontend practice

It is ideal for developers who want to practice application development across multiple stacks in a single repository.
