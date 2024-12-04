# Car Dealership Management System

## Description of the Project

The Dealership Management System is a Java-based application designed to manage vehicle inventories,
contracts, and dealership operations for a car dealership business.
The project utilizes a MySQL database to store and manage data about vehicles, dealerships, sales,
and leases, providing a user-friendly interface for performing key operations.

## User Stories

- As a user, I want to display the list of all vehicles so that I can see all the cars available in the inventory.
- As a user, I want to search for vehicles based on price, make, year, mileage, or type so that I can find cars that match my preferences.
- As an admin, I want to add a new vehicle to the inventory so that it becomes available for purchase or lease.
- As an admin, I want to remove a vehicle from the inventory so that it no longer appears in the listings.
- As an admin, I want to create a sales contract for a sold vehicle so that the sale is properly recorded.
- As an admin, I want to create a lease contract for a leased vehicle so that the lease agreement is documented.
- As a user, I want to view the inventory of a specific dealership so that I can see the cars available at that location.
- As an admin, I want to mark a vehicle as sold when a sales contract is created so that the inventory is updated accurately.


## Setup

Instructions on how to set up and run the project using IntelliJ IDEA.

### Prerequisites

- **IntelliJ IDEA**: Ensure you have IntelliJ IDEA installed. You can download it [here](https://www.jetbrains.com/idea/download/).
- **Java SDK**: Ensure Java SDK 8 or higher is installed and configured in IntelliJ.
- **MySQL Database**: Set up a MySQL database with the schema provided in the project.

### Database Setup

1. Run the SQL script provided in the project to create and populate the database.
2. Update the database connection details in the `BasicDataSource` configuration in the `Main` class.

### Running the Application in IntelliJ

1. Open IntelliJ IDEA.
2. Select "Open" and navigate to the directory where the project is located.
3. Wait for IntelliJ to index the files and set up the project.
4. Locate the `Main` class with the `public static void main(String[] args)` method.
5. Right-click on the `Main` class and select "Run" to start the application.

## Technologies Used

- **Java**: Version 8 or higher.
- **MySQL**: Database for storing inventory and contract data.
- **IntelliJ IDEA**: Integrated development environment.


## Future Work

Potential future enhancements include:

- Add refined filters for price, mileage, year, and other attributes.
- Implement a user-friendly graphical interface.

## Resources

- [Java Documentation](https://docs.oracle.com/javase/8/docs/)
- [MySQL Documentation](https://dev.mysql.com/doc/)
- YearUp Brightspace: https://yearup.brightspace.com/d2l/home
- Tutorials and guides from [W3Schools](https://www.w3schools.com/java/)

## Team Members

- **Enes YILMAZ**

## Thanks

Special thanks to:

- **Raymond** for continuous support and guidance.
- All team members and collaborators for their dedication and hard work.
