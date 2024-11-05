# Shoe Cleaning Business System

## Description

The Shoe Cleaning Business System is a web application designed to streamline client management for shoe cleaning businesses operating in multiple cities. It uses Supabase to handle data and authentication.

## Preview

![Dasboard](/github/dashboard.jpeg)
![Tables](/github/clients_table.jpeg)
![Activity](/github/activity_table.jpeg)

## Demo

[Live preview](https://dobirceanumihai.github.io/shoe-cleaning-business-system/#/login)

Accounts for testing:

* [Email: admin@email.com, Password: admin]  -  Admin role
* [Email: employee1@email.com, Password: employee]  -  Employee role

## Features

* Role-based authentification and access control (Admin, Employee).
* Branch-based client management.
* Add clients by providing their personal information, the pairs of shoes they brought in, the purchased cleaning services, and any additional details related to their order.
* Update and view client information.
* Delete client from the records.
* Search and filter functionality for tables.
* Notifications for orders with upcoming deadlines for tomorrow and day after tomorrow.
* Filters for orders with upcoming deadline for tomorrow and day after tomorrow.

### Admin Only Features

* Dashboard to view revenue, sales, client metrics, and service metrics over a selected time period and branch.
* Only the data from the paid orders will be displayed in the dashboard.
* Additional table for managing business accounts.
* Add, update, view, delete branches.
* Add, update, view, delete cleaning services.
* Activity table to view changes made in the clients table.
* User profile update (username, branch).

## Built With

* [![Angular][Angular.io]][Angular-url] - Version 18.2.11
* [![Supabase][Supabase.io]][Supabase-url] - Version 2.46.1

[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/

[Supabase.io]: https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white
[Supabase-url]: https://supabase.com/
