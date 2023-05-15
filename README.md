# aeki-webshop

This is a furniture webshop that is built using various technologies, including Asp.Net Core, Entity Framework, Asp.Net Identity, Sessions, and SqlServer.

## Technologies Used

- Asp.Net Core: Asp.Net Core is an open-source and cross-platform framework for building modern web applications. It provides a unified programming model for building web applications using different frameworks such as MVC, Web API, and SignalR.

- Entity Framework: Entity Framework is a popular Object-Relational Mapping (ORM) framework that simplifies the interaction between a database and a .NET application. It allows developers to work with relational data using domain-specific objects.

- Asp.Net Identity: Asp.Net Identity is a membership system that provides an easy way to manage user authentication and authorization. It is built on top of the ASP.NET Identity framework and provides features such as login, logout, registration, and password reset.

- Sessions: Sessions are a way to store user data on the server-side. It allows developers to store information that can be accessed across multiple requests. In the case of a webshop, sessions can be used to store information about a user's shopping cart or preferences.

- SqlServer: SqlServer is a relational database management system (RDBMS) developed by Microsoft. It is widely used in enterprise applications due to its robustness, scalability, and security features.

## Getting Started

To get started with the aeki-webshop, follow these steps:

1. Clone the repository using the following command:
```bash
git clone https://github.com/andrograf/aeki-webshop.git
```
2. Open the solution in Visual Studio.
3. Build the solution to restore the required NuGet packages.
4. Run the database migrations using the following command:
```bash
dotnet ef database update
```
5. Run the application using the following command:
```bash
dotnet run
```

## License
The aeki-webshop project is licensed under the MIT License. See the LICENSE file for more information.
