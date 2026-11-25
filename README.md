# Hospital Management System (Java)

A group coursework project developed using Java and Object-Oriented Programming (OOP) concepts to manage hospital operations and records.

Developed for Object-Oriented Programming at Universiti Tunku Abdul Rahman (UTAR).

## Project Objective

Develop a Hospital Management System (HMS) that allows users to manage hospital-related information, including doctors, patients, medical supplies, laboratories, facilities and administrative staff.

The system aims to organise hospital records and provide basic functions for adding and displaying information.

## Technologies

- Java
- Eclipse IDE
- Object-Oriented Programming (OOP)
- UML Class Diagram

## System Modules

| Module | Description |
| --- | --- |
| Doctors | Manage doctor information, specialisations and working hours |
| Patients | Manage patient records, diseases and admission status |
| Medical | Manage medicine information, manufacturers, expiry dates and costs |
| Laboratories | Manage laboratory information and service costs |
| Facilities | Manage hospital facility records |
| Staff | Manage administrative staff information and salaries |

## OOP Concepts

The project applies object-oriented programming principles through separate classes for different hospital entities.

- **Encapsulation** – Organise data fields and related methods within individual classes.
- **Single Responsibility Principle** – Assign specific responsibilities to different classes.
- **Object-Oriented Design** – Represent hospital entities using classes and objects.
- **Modular Design** – Separate the hospital management functions into different modules.

## Main Features

- Display a welcome message with the current date and time.
- Provide a main menu for accessing six hospital management modules.
- Add new records for different hospital entities.
- Display existing records from the corresponding lists.
- Navigate between the previous section and the main menu.
- Initialise hospital records using arrays or dynamic arrays (ArrayList).

## System Design

The system consists of several main classes:

- `HospitalManagement`
- `Doctor`
- `Patient`
- `Staff`
- `Medical`
- `Lab`
- `Facility`

A UML Class Diagram is used to illustrate the classes, attributes, methods and relationships within the system.

## Contributors

| Team Member | Files | Contributions |
| --- | --- | --- |
| Yew Kai Qian | `Facility.java`, `MainGUI.java` | Facility management and JavaFX graphical user interface |
| Leong Di Hao | `BaseRecord.java`, `Doctor.java`, `Patient.java`, `Ambulance.java` | Inheritance, Open/Closed Principle and ambulance module extension |
| Chong Wei Ni | `Staff.java`, `Medical.java`, `InputValidator.java` | Staff and medical modules, input validation and exception handling |
| Liew Jia Min | `Lab.java`, `HospitalManagement.java` | Laboratory module, ArrayList management, controller logic and system integration |

## My Contributions

- Developed `Lab.java` to manage laboratory information and service costs.
- Implemented controller logic in `HospitalManagement.java` to coordinate the hospital modules.
- Used ArrayLists to initialise and manage hospital records.
- Integrated the individual modules into the overall hospital management system.
## Project Context

This project was developed as part of the UCCD2044 Object-Oriented Programming coursework at Universiti Tunku Abdul Rahman (UTAR), June 2026 Term.

The assignment focuses on applying Java programming and object-oriented design principles to a practical hospital management scenario.
