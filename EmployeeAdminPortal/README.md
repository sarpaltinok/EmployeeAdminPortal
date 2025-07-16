# 🧑‍💼 Employee Admin Portal - ASP.NET Core Web API

A simple backend API project built with ASP.NET Core (.NET 8) and Entity Framework Core to manage employee records. It demonstrates how to implement full CRUD (Create, Read, Update, Delete) operations and connect with a SQL Server database using EF Core.

---

## 🚀 Technologies Used

- ASP.NET Core Web API (.NET 8)
- Entity Framework Core
- Microsoft SQL Server Express
- Swagger UI (for API testing)
- Visual Studio 2022

---

## 📌 Features

- ✅ Add new employee
- 🔍 Get employee list
- ✏️ Update employee details
- ❌ Delete employee record
- 🔗 MSSQL Database integration using EF Core
- 🌐 RESTful API design with Swagger UI support

---

## Getting Started

1. Clone the repository:
2. Open the solution in Visual Studio.
3. Update the connection string in `appsettings.json` to match your database.
4. Run database migrations (if needed).
5. Start the project (F5 or Ctrl+F5).

## API Endpoints

- `GET /api/employees` - List all employees
- `GET /api/employees/{id}` - Get employee by ID
- `POST /api/employees` - Add a new employee
- `PUT /api/employees/{id}` - Update employee details

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

[MIT](LICENSE)
