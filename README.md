# Api-SGIT - Idea & Topic Management System

##  Overview
Api-SGIT is a backend system designed to manage ideas and topics, focusing on scalability, data organization, and clean architectural patterns. The project applies modern software engineering principles to ensure maintainability, performance, and data consistency.

##  Data Engineering Perspective
This project highlights:
- Data modeling in both relational and non-relational databases
- Data migration strategy (SQL → NoSQL)
- Separation of read and write operations using CQRS
- Structured data validation and transformation
- Scalable data access patterns

##  Architecture
The system follows **Clean Architecture** principles, organized into four layers:

- **Domain Layer** → Core business rules and entities  
- **Application Layer** → Use cases and services  
- **Infrastructure Layer** → Data persistence and external integrations  
- **Presentation Layer** → API controllers  

Additionally:
- **DDD (Domain-Driven Design)** for domain organization
- **CQRS (Command Query Responsibility Segregation)** for optimized data access

##  Data Modeling

### Relational Database (SQL)
- Structured entities with relationships
- Used for transactional consistency

### Non-Relational Database (MongoDB)
- Flexible schema for scalability
- Optimized for read-heavy operations

##  Data Migration Strategy
- Migration performed using **Big-Bang approach**
- Data transferred from relational database to MongoDB
- Ensured:
  - Data consistency
  - Schema adaptation
  - Integrity validation

##  Data Flow

1. Client sends request to API
2. Controllers route requests (Command / Query separation)
3. Services process business logic
4. Data is validated and mapped
5. Persistence handled via ORM or NoSQL driver
6. Response returned to client

##  Technologies
- Java
- Spring Boot
- C#
- ASP.NET Core
- MySQL
- MongoDB

##  Key Patterns & Tools
- Clean Architecture
- DDD
- CQRS
- ORM (Entity Framework / Hibernate)
- AutoMapper
- FluentValidation

##  Testing
- Unit tests
- Integration tests
- Controller tests
- Use of mocks for isolation

##  Key Features
- Idea and topic management
- Layered architecture for scalability
- Data migration between databases
- Separation of read/write operations
- Robust validation and mapping

##  Highlights for Data Engineering
- Multi-database strategy (SQL + NoSQL)
- Data migration in production-like scenario
- Scalable query handling (CQRS)
- Structured data transformation

##  Repository

https://github.com/arthurczo/Api-SGIT.git