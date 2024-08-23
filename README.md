# EmployeeAdminPortal

<p>This is a .NET Core Web API that allows you to perform CRUD operations on employee data. 
  It provides endpoints for creating, retrieving, updating, and deleting employee records.</p>

Features Include
- Create new employee records
- Retrieve a list of all employees or a specific employee by ID
- Update existing employee records
- Delete employee records

Technologies Used
- .NET Core 8.0
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server Express

Getting Started
1. clone the repo
```console
foo@bar:~$ git clone https://github.com/shubd-dev/EmployeeAdminPortal.git
```
2. Open the solution in Visual Studio or your preferred IDE.
3. Configure the database connection string in the appsettings.json file.
4. Run the database migrations to create the necessary tables:
```console
foo@bar:~$ dotnet ef database update
```
5. Build and Run

