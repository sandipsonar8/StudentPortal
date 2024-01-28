# Student Portal CRUD Application

This is a simple **ASP.NET MVC CRUD application** for managing student information. The application uses **Entity Framework Core** to interact with a SQL Server database. It is built on the **.NET 8 MVC template** in **Visual Studio 2022**.

## Prerequisites

- [.NET SDK 8](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sandipsonar8/StudentPortal.git
   ```

2. **Open the solution in Visual Studio.**

3. **Set up the database:**
   - Open `appsettings.json` and update the connection string if necessary.
   - Run the following commands in the Package Manager Console:
     ```bash
     Update-Database
     ```

4. **Build and run the application.**

   ```bash
   dotnet run
   ```

   The application should be accessible at `http://localhost:5000`.

## Features

- **List Students:** View a list of all students.
- **Add Student:** Add a new student to the database.
- **Edit Student:** Update information for an existing student.
- **Delete Student:** Remove a student from the database.
  
## Project Structure

- **Controllers:** Contains MVC controllers for handling HTTP requests.
- **Models:** Defines the data models used in the application.
- **Views:** Contains the Razor views for rendering HTML.
- **Data:** Contains the database context and migrations.

## Technologies Used

- **ASP.NET Core MVC:** The web framework.
- **Entity Framework Core:** For database access and operations.
- **SQL Server:** The relational database for storing student information.
