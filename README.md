This project is a simple car rental management system implemented in Java. It consists of three main classes: CARRENTAL, Customer, and RentalAgency, along with a main class to demonstrate the system's functionality. Here's a brief description of each component:

CARRENTAL Class:

Represents a car available for rent.
Contains attributes such as licensePlate, model, and isRented to track whether the car is currently rented.
Provides methods to rent (rentCar) and return (returnCar) the car, ensuring proper state management.
Customer Class:

Represents a customer in the car rental system.
Contains attributes such as name and driverLicense.
RentalAgency Class:

Manages the list of cars and customers.
Provides methods to add cars (addCar) and customers (addCustomer) to the system.
Includes functionality to rent a car to a customer (rentCarToCustomer) and return a car (returnCarFromCustomer).
Offers a method to get a list of available cars (getAvailableCars).
main Class:

Demonstrates the functionality of the car rental system.
Creates instances of CARRENTAL and Customer, adds them to the RentalAgency, and performs rent and return operations.
Handles exceptions to manage errors such as attempting to rent an unavailable car or returning a car that is not rented.
