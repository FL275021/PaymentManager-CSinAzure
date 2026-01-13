# System for managing payments made by company teams(Customer service, Marketing, etc)

Each user can register a payment which will be linked to their corresponding team. 
An user can have 1 of 3 different roles:

-Employes: Login, Logout, Make a Payment, Check own payments. 

-Managers: Monthly payments, List exceeding users, aswell of all of the above options.

-Admins: Manage all users, payments, expenses types and teams, aswell of all of the above options.

### Technologies used:
### Azure
Client MVC and API resources, aswell as the database are all independently running in Azure.

### Solution API restFull
Utilizes clean architecture following the Solid principle.  

### JWT (JSON Web Token) Bearer Authentication:
A JWT is a self-contained token that encapsulates information for an API resource or a client.
