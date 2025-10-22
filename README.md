## Noticeboard in Java with graphical interface and client-server

## Project Description

This project implements a noticeboard application in Java featuring a graphical user interface (GUI) and a client-server architecture. It allows users to create, modify, delete and search for notices. The client application provides a user-friendly interface for interacting with the noticeboard while the server manages the storage and retrieval of notice data. The client communicates with the server using sockets to perform various operations.

## Features

*   **Graphical User Interface (GUI):** An intuitive interface for easy interaction.
*   **Client-Server Architecture:** Enables multiple clients to connect and interact with the noticeboard.
*   **Create Notices:** Users can create and post new notices with details like name, surname, job, phone, country, username and date.
*   **Modify/Delete Notices:** Allows users to modify or delete existing notices based on the username.
*   **Search Notices:** Enables users to search for notices based on specific criteria such as date ranges.
*   **User Authentication:** Implements a login and registration system to manage user accounts.
*   **Socket Communication:** Uses sockets for communication between the client and server.

## Table of Contents

*   [Project Description](#project-description)
*   [Features](#features)
*   [Installation](#installation)
*   [Usage](#usage)
*   [Dependencies](#dependencies)
  
## Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/panoschron97/Noticeboard_in_java_with_graphical_interface_and_client_server.git
    cd Noticeboard_in_java_with_graphical_interface_and_client_server
    ```

2.  Navigate to the `Noticeboardclient` and `Noticeboardserver` directories separately.

3.  Open each project in your preferred Java IDE (e.g., NetBeans).

4.  Ensure that the `Noticeboardclient` project references the `Noticeboardserver` project allowing them to communicate.

## Usage

1.  First run the `Noticeboardserver` project to start the server.

    *   In NetBeans right-click on the `Noticeboardserver` project and select "Run".
2.  Then run the `Noticeboardclient` project to start the client application.

    *   In NetBeans right-click on the `Noticeboardclient` project and select "Run".
3.  The client application will present a login window. You can either log in with existing credentials or register a new account.
4.  Once logged in you can create, modify, delete and search for notices using the menu options.

## Dependencies

*   **Java Development Kit (JDK):** Required to compile and run the Java code.
*   **NetBeans IDE (Optional):** Recommended IDE for developing and managing the project.
*   **Java Swing:** Used for creating the graphical user interface.
*   **Java IO:** Used for file operations like reading and writing data.
*   **Java Net:** Used for socket programming to implement the client-server communication.
