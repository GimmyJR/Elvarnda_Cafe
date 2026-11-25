# Elvarnda Cafe

A Windows desktop **point-of-sale (POS) system for a cafe**, built with C# Windows Forms and SQL Server.

## Features

- Manage categories, products and tables (add and view screens)
- POS screen to build an order for a table
- Checkout screen and bill list
- Printable bill report (`rptBill`)
- Local SQL Server database (`ElvarandaCafe.mdf`) and a `SQLQuery1.sql` script

## Tech stack

C#, .NET Framework Windows Forms, ADO.NET (SQL Server), report viewer.

## Getting started

1. Open `Elvarnda Cafe.sln` in Visual Studio on Windows.
2. Make sure SQL Server (LocalDB or Express) is available and update the connection string in `Elvarnda Cafe/MainClass.cs` to point at the included `ElvarandaCafe.mdf` or a database created from `SQLQuery1.sql`.
3. Build and run.

## Structure

```
Elvarnda Cafe/Model/    data entry and POS forms
Elvarnda Cafe/View/     category, product and table list forms
Elvarnda Cafe/Reports/  bill report
MainClass.cs            database connection and shared helpers
```
