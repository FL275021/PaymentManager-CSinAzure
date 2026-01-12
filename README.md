
# System for managing payments made by company teams(Customer service, Marketing, etc)

Each user can register a payment which will be linked to their corresponding team. An user can have 1 of 3 different roles(Admin, Manager, Employe), and each has both unique and shared options:

-Employes: Login, Logout, Make a Payment, Check own payments. 

-Managers: Monthly payments, List exceeding users, aswell of all of the above options.

-Admins: Manage all users, payments, expenses types and teams, aswell of all of the above options.

### Client MVC and API resources, aswell as the database are all up in Azure.

### Solution API restFull - utilizes clean architecture following the Solid principle.  

JWT (JSON Web Token) Bearer Authentication:
A JWT is a self-contained token that encapsulates information for an API resource or a client. The client which requested the JWT can request data from an API resource using the Authorization header and a bearer token.
