# Lap Shop

Lap Shop is a modern ASP.NET Core MVC e-commerce application for selling laptops and related products, with an admin panel for managing store operations.

## Overview

This project provides a complete online shopping experience with:
- A product catalog for laptops and accessories
- Category-based product organization
- Customer and supplier management
- Sales and purchase invoice handling
- Discount and slider management
- A clean admin-oriented data model built with Entity Framework Core

## Features

- Browse products and categories
- Manage items, prices, and images
- Track purchase and sales invoices
- Handle customers, suppliers, and business information
- Support discounts and promotional sliders
- Built with ASP.NET Core MVC and SQL Server

## Tech Stack

- ASP.NET Core MVC
- .NET 10
- Entity Framework Core
- SQL Server
- Bootstrap and Razor Views

## Prerequisites

Before running the project, make sure you have:
- .NET SDK 10 or later
- SQL Server installed and running
- Visual Studio 2022 / VS Code

## Getting Started

1. Clone the repository
   ```bash
   git clone <your-repository-url>
   cd Lap_Shop-
   ```

2. Restore dependencies
   ```bash
   dotnet restore
   ```

3. Configure the database
   - This project uses SQL Server through Entity Framework Core.
   - Update the connection string in the database context if needed to match your local SQL Server instance.

4. Run the application
   ```bash
   dotnet run
   ```

5. Open your browser
   - Navigate to: http://localhost:5000
   - Or the port shown in the terminal output

## Project Structure

- Controllers/ - MVC controllers
- Models/ - Entity Framework models and database context
- Views/ - Razor views for the storefront and UI
- wwwroot/ - Static files such as CSS, JavaScript, and images
- Migrations/ - Database migration files

## Database

The application uses Entity Framework Core migrations for database management. If you want to apply migrations:

```bash
dotnet ef database update
```

## Notes

- The project is currently configured for a local SQL Server setup.
- For production deployment, it is recommended to move sensitive configuration values to environment variables or secure configuration providers.

## License

This project is currently unlicensed. Add a license if you plan to share or distribute it publicly.
