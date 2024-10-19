# Multi-User Client-Server Application 

The Multi-User Client-Server Application is a project developed for the Object-Oriented Programming module. This application features a database-driven client-server system, offering functionalities such as data access, JSON communication, and multithreading.

## Objectives

- Design, implement, and test a database-driven client-server application.
- Create a Data Access Layer for efficient database access.
- Develop a multithreaded server to handle multiple client requests.
- Facilitate data exchange between client and server using JSON format with the GSON parser.
- Implement binary data stream exchange.

## Features

- **Retrieve All Entities:** Display a list of all entities in the database.
- **Find Entity by Key:** Retrieve and display a specific entity using its key.
- **Delete Entity by Key:** Remove a specified entity from the database.
- **Insert Entity:** Collect data, create an entity, and insert it into the database.
- **Update Entity by ID:** Modify an existing entity using its ID.
- **Filter Entities:** Retrieve and display entities that match a specified filter.
- **Serialize Entities to JSON:** Convert a list or a single entity into JSON format.
- **Display Entity by ID:** Implement communication to show an entity based on its ID.
- **Display All Entities:** Enable client-server communication to display all entities.
- **Add Entity:** Facilitate client-server communication for adding new entities.
- **Delete Entity by ID:** Enable deletion of an entity by its ID through client-server communication.
- **Download Images:** Implement communication to retrieve image files.
- **Exit Application:** Notify the server when the client is quitting and terminate the client session.

## Technologies Used

- **Programming Language:** Java
- **Database:** MySQL
- **Data Access:** DAO, DTO, and associated interfaces
- **Data Format:** JSON (using GSON parser)
- **Multithreading:** Java multithreading
- **Testing Framework:** JUnit

## Installation Requirements

- Java Development Kit (JDK)
- MySQL Database
- GSON Library
- Git

