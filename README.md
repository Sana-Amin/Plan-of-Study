# Plan-of-Study
The Plan of Study program is a database-driven web application that utilizes the Model-View-Controller (MVC) architectural pattern using the ASP.NET MVC Framework. This architectural pattern separates the Plan of Study application into three main logical components and each component is designed to handle specific development aspects of the application.

 

1.     Model

2.     View

3.     Controller

 

The goal of the Plan of Study program is to demonstrate a practical example of MVC Framework development by creating an online course catalog with navigation by category or page feature, a shopping cart that allows users to add or remove courses, and a checkout feature where users can enter shipping details. Lastly, there is a secure administration feature that allows only logged-in administrators to perform create, read, update, and delete (CRUD) operations. A well-designed MVC application starts with a well-designed model, and I make sure to add the objects, processes, and rules that define the domain model with a course, order, and shipping repositories backed by SQL Server instance and the Entity Framework. I created paginated lists of courses and dependency injection and a friendly URL scheme. This makes it easier for views and controllers to expose the domain to the clients in a consistent manner.
