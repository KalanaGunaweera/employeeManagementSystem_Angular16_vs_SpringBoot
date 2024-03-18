# Employee Management System (EMS)

#### Description:
The Employee Management System (EMS) is a comprehensive CRUD (Create, Read, Update, Delete) application designed to efficiently manage employee-related operations within a small company. It provides a user-friendly interface for seamless employee record management. The EMS is built using Angular 16 as the frontend framework and Spring Boot as the backend framework.

<img src="https://github.com/learn-spring-boot-and-spring-security/EmployeeManagementSystem_Angular16_and_SpringBoot/blob/main/SnipShots_UI/Add_Employee_UI.PNG" width="600">
<img src="https://github.com/learn-spring-boot-and-spring-security/EmployeeManagementSystem_Angular16_and_SpringBoot/blob/main/SnipShots_UI/Update_Employee_UI.PNG" width="600">
<img src="https://github.com/learn-spring-boot-and-spring-security/EmployeeManagementSystem_Angular16_and_SpringBoot/blob/main/SnipShots_UI/View_EmployeeList_UI.PNG" width="600">
<img src="https://github.com/learn-spring-boot-and-spring-security/EmployeeManagementSystem_Angular16_and_SpringBoot/blob/main/SnipShots_UI/View_Employee_UI.PNG" width="600">

The project consists of the following files:

1. `app.component.ts`: This file contains the main component of the Angular application. It handles the routing and navigation between different pages.

2. `employee.service.ts`: This file defines the EmployeeService class responsible for handling HTTP requests to the backend API. It encapsulates functions for creating, reading, updating, and deleting employee records.

3. `employee.model.ts`: This file defines the Employee class that represents the structure of an employee object. It includes properties such as name, designation, contact information, and department.

4. `EmployeeController.java`: This file contains the backend controller class implemented using Spring Boot. It handles incoming HTTP requests from the frontend and performs the necessary CRUD operations on employee records.

Throughout the development process, various design choices were made to ensure a smooth user experience and efficient data management. For instance, we implemented a responsive user interface using Angular 16, allowing users to interact with the system seamlessly across different devices. We also utilized Spring Boot's powerful features, such as dependency injection and data persistence, to ensure secure and efficient communication between the frontend and backend components.

The EMS project aims to streamline employee management operations for small companies. By providing functionalities for creating, retrieving, updating, and deleting employee records, it enables efficient and accurate management of employee information. The user-friendly interface, combined with the powerful Angular 16 and Spring Boot frameworks, ensures a smooth and intuitive experience for users.

In addition to the core features mentioned above, the EMS project also includes authentication and authorization mechanisms to secure access to employee data. It implements role-based access control, allowing administrators to manage user roles and permissions effectively.

Contributions are welcome.



