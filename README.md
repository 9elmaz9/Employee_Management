# Employee Management System

![Employee Management System](https://i.pinimg.com/originals/05/2c/93/052c934eadb8a6504e8bb409ec96a1be.jpg)

This repository contains the source code for an Employee Management System implemented in Java using the Spring Framework.

## Features

- Allows users to view a list of employees
- Enables users to add new employees to the system
- Supports updating employee information
- Provides functionality for deleting employees from the system

## Installation

To run the Employee Management System locally, follow these steps:

1. Clone the repository to your local machine using the following command:
2. 
3. git clone https://github.com/9elmaz9/employee-management-system.git

   
2. Import the project into your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).

3. Build and run the project.

## Usage

Once the project is up and running, you can access the Employee Management System through a web browser. Here are the available endpoints:

- **View List of Employees**: Navigate to the homepage ("/") to see a list of all employees.

- **Add New Employee**: Access the "/showNewEmployeeForm" endpoint to display a form for adding a new employee.

- **Update Employee Information**: To update an existing employee's information, visit the "/showFormUpdate/{id}" endpoint, where "{id}" is the ID of the employee you want to update.

- **Delete Employee**: To delete an employee from the system, use the "/deleteEmployee/{id}" endpoint, where "{id}" is the ID of the employee to be deleted.

## Technologies Used

- Java
- Spring Framework
- Thymeleaf (for server-side HTML rendering)

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
