# Chat Application

## Introduction

The Chat Application is a C# project developed using WinForms and ADO.NET, designed to provide real-time messaging capabilities. It features user registration, login, and persistent chat history stored in a database.

## Features

- User registration and authentication
- Real-time messaging between users
- Persistent chat history
- User-friendly WinForms interface
- Database integration using ADO.NET

## Technologies Used

- Programming Language: C#
- Framework: WinForms
- Database: SQL Server
- Data Access: ADO.NET

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sanjaikrp/Chat-App-DB .git
    ```
2. Navigate to the project directory:
    ```sh
    cd Chat-App-DB 
    ```
3. Open the solution file (`ChatApplication.sln`) in Visual Studio.

4. Set up the database:
    - Create a new SQL Server database.
    - Run the SQL script provided in the `database` folder to create the required tables.

5. Update the connection string:
    - Open `App.config`.
    - Update the connection string to point to your SQL Server instance.

6. Build and run the project:
    - Press `F5` in Visual Studio to build and run the application.

## Usage

1. Register a new user or log in with existing credentials.
2. Start a new chat or join an existing one.
3. Send and receive messages in real-time.
4. View chat history.
