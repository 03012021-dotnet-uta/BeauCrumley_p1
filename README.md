# <img src="BeauCrumley_p1/wwwroot/favicon.png" alt="BEE Logo" width="50"/>Beau's Electronics Emporium 

## Project Description

Beau's Electronics Emporium is a concept for an e-commerce platform that could be used by an electronics hobby store. Included are much of the basic functionallity one might expect from an online store: User accounts, store pages with a display of products, and a functioning shoopping cart. The application is powered by ASP.NET Core and uses a web API to serve static pages to the client. 

## Technologies Used

* ASP.NET Core Web API
* Entity Framework Core
* C#, JavaScript/HTML/CSS, SQL

## Features

* Register new accounts and login.
* Browse products of a store.
* Add/remove items from cart.
* Have order total viewable any time.
* Place orders that automatically update the inventory levels of a store.

To-do list:
* Store selection page.
* Displaying order history of a logged in user.
* (Admin) Display/Sort/Filter all orders by store/product/revenue/customer/etc.

## Getting Started
   
1. git clone [https://github.com/03012021-dotnet-uta/BeauCrumley_p1.git](https://github.com/03012021-dotnet-uta/BeauCrumley_p1/ "Project Repository")
2. In order to get the project up and running a database will need to be created. Included in the `./Repository/Data/` folder is a file, `DatabaseSetup.sql`, that should have everything needed to create and seed a database to get started.
3. Open a CLI and make sure it is pointed at the `./BeauCrumley_p1/` directory and run the following command: `dotnet run`.
     * NOTE: If there is an issue executing the command, ensure the .NET CLI is installed. Learn more at [Microsoft](https://dotnet.microsoft.com/download ".NET Download")
4. Once the build has completed open a browser at `localhost:5001`.

## License

This project uses the following license: [MIT License](https://mit-license.org/ "MIT License").
