Car Rental System
Overview
This project outlines the design for a Car Rental System, focusing on the key entities: Car, Customer, RentalAgency, and a Test component to demonstrate interactions between these entities.
Entities

Car
Represents a car available for rent.
Attributes:
id: Unique identifier for the car.
make: Car manufacturer.
model: Car model.
year: Year of manufacture.
rentalRate: Rental rate per day.
isAvailable: Availability status of the car.
Key Actions:
Retrieve car details.
Update car availability status.

Customer
Represents a customer renting a car.
Attributes:
id: Unique identifier for the customer.
name: Customer's name.
email: Customer's email.
phoneNumber: Customer's contact number.
Key Actions:
Retrieve customer details.
Update customer information.

RentalAgency
Manages the car rental operations.
Attributes:
name: Name of the rental agency.
cars: List of cars available for rent.
customers: List of registered customers.
Key Actions:
Add a car to the inventory.
Remove a car from the inventory.
Register a new customer.
Rent a car to a customer.
Mark a car as returned.
Retrieve agency details and status.

Test
Demonstrates the functionality of the Car Rental System.
Key Actions:
Instantiate Car, Customer, and RentalAgency entities.
Simulate adding cars and customers.
Demonstrate renting and returning cars.
Validate system operations through printed outputs or assertions.
