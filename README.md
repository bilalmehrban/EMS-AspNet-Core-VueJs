# Employee Management System - EMS

Employee Management System, A Complete HRM suite for day to day tasks of a small business. EMS is built using Clean Architecture [Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html) with ASP.NET Core and Vue.js

## Clean Architecture (An implementation of Onion Architecture)

Clean architecture is close implementation of Onion architecture. It uses the same Inversion of Control principles. It contains the following layers:

 * **Domain layer** contains the entities or types that can be use in the application and it does not have any dependency.
 * **Application layer** contains business logic and depends on domain layer. 
 * Both **Infrastructure and Api layers** depend only on Application layer. Infrastructure contains external concerns like the type of database and authentication mechanism while Api layer is responsible for presenting the data to the client application like a website or a mobile app.

![Clean architecture](https://github.com/bilalmehrban/EMS-AspNet-Core-VueJs/blob/main/Clean%20Architecture.png)

## Give a Star! :star:

If you like or are using this project, please give it a star. Thanks!

## Versions

The main branch is using .NET Core Version 3.1 and Vue.js version 3.0

## Using the GitHub Repository

To get started based on this repository, you need to get a copy locally. You have three options: fork, clone, or download. Most of the time, you probably just want to download.

You should **download the repository**, unblock the zip file, and extract it to a new folder if you just want to play with the project or you wish to use it as the starting point for an application.

You should **fork this repository** only if you plan on submitting a pull request. Or if you'd like to keep a copy of a snapshot of the repository in your own GitHub account.

You should **clone this repository** if you're one of the contributors and you have commit access to it. Otherwise you probably want one of the other options.
