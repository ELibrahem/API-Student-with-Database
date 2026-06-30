# API-Student-with-Database
CRUD operation in project Api student for RESTful APIs and database



## Student Management API 🎓
A robust RESTful API built with .NET to manage student academic records. This project focuses on a clean, layered architecture to ensure scalability, maintainability, and data integrity.

## 🚀 Overview
This API provides a centralized system for performing CRUD operations on student data. It connects to a SQL Server database, utilizing Entity Framework Core to manage data interactions efficiently.

##🛠️ Tech Stack
Language: C#

Framework: .NET 10

ORM: Entity Framework Core

Database: SQL Server

Architecture: Layered Architecture (API, Business, Data Access)

## 📂 Project Structure
This project follows a clean architecture approach to separate concerns:

/API                # Controllers, Middleware, and Configuration
/BusinessLayer      # Services, Logic, and Data validation
/DataLayer          # Repositories, DbContext, and Migrations
/Models             # DTOs and Database Entities

##⚙️ Key Features
Student Management: Full CRUD (Create, Read, Update, Delete) for student records.

Data Persistence: Integrated with SQL Server for permanent data storage.

Layered Design: Separated business logic from data access for clean, testable code.

### 🚀 How to Run
Clone the repo:

1. Bash ``
git clone https://github.com/ELibrahem/API-Student-with-Database.git
``
2. Setup Database:

Open appsettings.json.

Update the ConnectionStrings to match your local SQL Server instance.

3. Run Migrations:
Run the following command in the Package Manager Console to create the database:

4. Bash
Update-Database
Launch: Press F5 or dotnet run to start the API.


##📌 API Endpoints

https://docs.google.com/spreadsheets/d/1nRlfP541-uy8hwSNT3z_q1QOL3OYtyBZExz8otrQnBU/edit?usp=sharing


💡 Notes
Make sure to keep your appsettings.json local and do not push sensitive connection strings to the remote repository.
