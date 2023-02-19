# Capstone: Restaurant Reservation System

https://restaurant-reservation-system-czoy59r9c-ravneet998.vercel.app/dashboard
<img width="1359" alt="restaurant homepage" src="https://user-images.githubusercontent.com/109993408/219911180-5124093d-68e0-4a40-88a4-43c997f68426.png">


> You have been hired as a full stack developer at _Periodic Tables_, a startup that is creating a reservation system for fine dining restaurants.
> The software is used only by restaurant personnel when a customer calls to request a reservation.
> At this point, the customers will not access the system online.

There are no user stories for deployment: it is expected that you will deploy the application to production after you finish a user story.

There are no user stories for logging: it is expected that you will add logging to the application with enough detail to help you diagnose issues in production.

## Existing files

This repository is set up as a *monorepo*, meaning that the frontend and backend projects are in one repository. This allows you to open both projects in the same editor.

As you work through the user stories listed later in this document, you will be writing code that allows your frontend and backend applications to talk to each other. You will also write code to allow your controllers and services to connect to, and query, your PostgreSQL database via [Knex](http://knexjs.org/).

<h2> API Documentation </h2>
/reservations - GET: List all reservations & POST: Create a new reservation
//reservations/:reservation_id/status - PUT: Update a reservation's status. Options being "booked", "seated", "cancelled", or "finished".
/tables - GET: List all tables & POST: Create a new table
/tables/:tableId/seat - PUT and DELETE to update or remove a reservation id from a table, and then update the reservation status

<h2> Technology </h2>
JavaScript
HTML
CSS and Bootstrap
NodeJS
PostgreSQL
React
REST APIs
Express

<h2> Installation </h2>
Fork and clone this repository.
Run cp ./back-end/.env.sample ./back-end/.env.
Update the ./back-end/.env file with the connection URL's to your ElephantSQL database instance.
Run cp ./front-end/.env.sample ./front-end/.env.
You should not need to make changes to the ./front-end/.env file unless you want to connect to a backend at a location other than http://localhost:5001.
Run npm install to install project dependencies.
Run npm run start:dev to start your server in development mode.

<h3> /search <h3>
<img width="894" alt="search" src="https://user-images.githubusercontent.com/109993408/219914101-d4907c46-d9f3-4ea7-8583-309a97cdbf53.png">

<h3> reservations/new <h3>

<img width="1198" alt="new" src="https://user-images.githubusercontent.com/109993408/219914473-f5fb72e4-11a5-434a-8e7a-7d4b37bc5d75.png">

