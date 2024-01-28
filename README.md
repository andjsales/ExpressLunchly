# Express Lunch.ly

### Requirements
- Node.j
- npm (Node Package Manager)
- PostgreSQL

### Prerequisites
- npm install
- createdb lunchly
- psql lunchly < data.sql
- nodemon server.js

### Usage
Viewing Customers: 
Navigate to the main page to see a list of all customers
- http://localhost:3000/

Adding Customers: 
Click on the "Add a Customer" link and fill in the customer details.
- http://localhost:3000/add/

Show a customer, given their ID:
- http://localhost:3000/:id/

Show form to edit a customer:
- http://localhost:3000/:id/edit/

Creating Reservations: 
From a customer's detail page, use the "Add" button to add a new reservation.
- http://localhost:3000/

