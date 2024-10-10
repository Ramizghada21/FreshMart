POSales - Point of Sale (POS) System
POSales is a desktop-based point of sale system built with C# .NET and Windows Forms. This application is designed for managing sales transactions, monitoring daily sales, and handling cashier operations. It offers a simple, user-friendly interface suitable for retail businesses, providing features like sales tracking, cashier management, and reporting.

Features
Daily Sales Summary: Track and manage daily sales for all or specific cashiers, with date range filtering.
Cashier Management: Add, edit, and manage cashier details, including assigning roles.
Product Management: Manage product details, including product codes, descriptions, and prices.
Transaction Handling: Process customer transactions and generate sales receipts.
Sales Reports: Generate detailed sales reports for specified date ranges, with export and print options.
Cancel Orders: Cancel individual transactions with proper logging and authentication.
Technologies Used
C# .NET: Core application built using Windows Forms (WinForms).
SQL Server: Database used for storing sales, cashier, and product data.
Windows Forms (WinForms): Provides the user interface for managing transactions, products, and users.
Crystal Reports: Integrated reporting feature for generating sales reports.
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/posales.git
Open the solution file (POSales.sln) in Visual Studio.

Restore NuGet packages if prompted.

Update the database connection string in DBConnect.cs file to match your SQL Server setup:

csharp
Copy code
public string myConnection() 
{
    return @"Data Source=your_server;Initial Catalog=pos_db;Integrated Security=True";
}
Build and run the application in Visual Studio.

Screenshots
Main Dashboard: Overview of sales and cashier operations.
Sales Report: Filter sales data by date or cashier.
Transaction History: Manage and track sales transactions.
License
This project is licensed under the MIT License. See the LICENSE file for details.

