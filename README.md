# Subscription Management Tool


This is a simple ASP.NET Core MVC application for managing subscriptions. The application allows users to add, edit, delete, and view subscriptions, as well as receive alerts for upcoming payments.

Features
  •	Add Subscription: Add new subscriptions with details like name, description, price, payment day, and duration. <br>
  •	Edit Subscription: Update existing subscription details. <br>
  •	Delete Subscription: Remove subscriptions from the list. <br>
  •	View Subscriptions: Display a list of all subscriptions. <br>
  •	Upcoming Payment Alerts: Notify users about upcoming payments within the next 7 days. <br>
  
Technologies Used
  •	ASP.NET Core MVC: For building the web application. <br>
  •	Entity Framework Core: For database operations. <br>
  •	SQL Server: As the database. <br>
  •	Bootstrap: For styling the user interface. <br>
  
How to Run
  1.	Clone the repository.
  2.	Set up the database connection string in appsettings.json.
  3.	Run the migrations to create the database: "dotnet ef database update"
  4.	Start the application: "dotnet run"
  5.	Open apllication in your browser at "http://localhost:*specify port*"

Folder Structure
  •	Models: Contains the Subsription model. <br>
  •	Services: Contains the HomeService for business logic. <br>
  •	Controllers: Handles user requests and responses. <br>
  •	Views: Contains Razor views for the user interface. <br>
  
License <br>
This project is licensed under the MIT License.
