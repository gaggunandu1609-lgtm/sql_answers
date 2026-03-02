<!-- Select all columns from the Customers table. -->
-SELECT * FROM Customers;
<!-- Select only the CustomerName column from Customers. -->
-SELECT CustomerName FROM Customers;
<!-- Select distinct Country from the Customers table. -->
-SELECT distinct Country from Customers;
<!-- Select the City column from the Customers table. -->
-SELECT City FROM Customers;
<!-- Select all Products where the Price is greater than 50. -->
-SELECT * FROM Products WHERE Price > 50;
<!-- Select all Orders where the OrderID is exactly 10248. -->
-SELECT * FROM Orders WHERE OrderID = 10248;
<!-- Select all Customers who live in 'Germany'. -->
-SELECT * FROM Customers WHERE Country = 'Germany';
<!-- Select all Employees who were hired after the year 1993. -->
-SELECT * FROM Employees WHERE HireDate > '1993-12-31';
<!-- Select all Products where the CategoryID is 1. -->
-SELECT * FROM Products WHERE CategoryID = 1;
<!-- Select the top 5 Customers. -->
-SELECT TOP 5 * FROM Customers;
<!-- Select the first 10 Products. -->
-SELECT TOP 10 * FROM Products;
<!-- Select unique Cities from the Customers table. -->
-SELECT DISTINCT City FROM Customers;
<!-- Select all Orders where the ShipCountry is 'USA'. -->
-SELECT * FROM Orders WHERE ShipCountry = 'USA';
<!-- Select all Customers whose CustomerID starts with the letter 'A'. -->
-SELECT * FROM Customers WHERE CustomerID LIKE 'A%';
<!-- Select all Products with a price between 10 and 20. -->
-SELECT * FROM Products WHERE Price BETWEEN 10 AND 20;
<!-- Select all Orders where the OrderDate is NULL. -->
-SELECT * FROM Orders WHERE OrderDate IS NULL;
<!-- Select all Employees whose LastName is 'Davolio'. -->
-SELECT * FROM Employees WHERE LastName = 'Davolio';
<!-- Select all Products that are NOT in category 2. -->
-SELECT * FROM Products WHERE CategoryID != 2;
<!-- Select all Customers living in either 'Germany' or 'France'. -->
-SELECT * FROM Customers WHERE Country IN ('Germany', 'France');
<!-- Select all Customers who are NOT from the 'UK'. -->
-SELECT * FROM Customers WHERE Country <> 'UK';