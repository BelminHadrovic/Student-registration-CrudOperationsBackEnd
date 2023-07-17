<h1>CRUD Operations Backend in C#</h1>

This repository contains a simple CRUD (Create, Read, Update, Delete) operations backend implemented in C#. The purpose of this project is to demonstrate a basic RESTful API that allows users to interact with a database through standard HTTP methods.

<h2>Prerequisites</h2>
<br>
Before you begin, make sure you have the following installed:
</br>
<br>.NET Core SDK</br>
<br>Any preferred Integrated Development Environment (IDE) that supports C# (Visual Studio, Visual Studio Code, etc.)</br>
<br>A database server (e.g., Microsoft SQL Server, MySQL, PostgreSQL)</br>
<br>NuGet packages for Entity framework(Microsoft.EntityFrameworkCore.Design; Microsoft.EntityFrameworkCore.Tools; Microsoft.EntityFrameworkCore.SqlServer)</br>

<h2>Getting Started</h2>
Clone this repository to your local machine.

Open the project in your preferred IDE.

Configure the Database:

Create a new database on your database server to use with this project.

Update the database connection string in the appsettings.json file with your database information:

**"ConnectionStrings": {
    "DefaultConnection": "your-database-connection-string"
}**

Run the Migration:

Use the Entity Framework Core CLI or Package Manager Console to apply the initial migration and create the necessary tables in your database.

**CLI Command:**

dotnet ef database update

**Package Manager Console:**

Update-Database


<h2>API Endpoints</h2>
<br>The API provides the following endpoints:</br>

![Back](https://github.com/BelminHadrovic/Student-registration-CrudOperationsBackEnd/assets/124454034/5b261191-f639-45b7-97fd-5b2749c82297)


<h2>Testing the API</h2>

You can test the API using tools like Postman or cURL to interact with the endpoints and perform CRUD operations on the Item resource.





