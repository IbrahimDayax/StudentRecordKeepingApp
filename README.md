# Student Record Keeping App

This application is designed to keep track of students' records in a simple and efficient way. It allows users to add new records, search for a specific record, delete a record, delete all records, sort records, and display all records. The records are stored in a text file called database.txt.

The application consists of two classes: Student and App. The Student class defines the necessary data of every student that is to be stored in the system, which are name, studentID, courseID, and totalScore. The App class handles the GUI of the application and all the functionalities such as adding, searching, deleting and sorting the records.

## Prerequisites

    Java SE Development Kit (JDK) 8 or higher
    Java Integrated Development Environment (IDE) such as Eclipse, IntelliJ IDEA, or NetBeans

## Installation

    1. Download the source code from the link provided or clone the repository using the following command:

    ```git clone https://github.com/username/Student-Record-Keeping-App.git
    ```

    2. Import the project into your preferred IDE.
    3. Build and run the project.

## Getting Started

    Launch the app by running the main method in the App class.
    The app's main window will appear.
    The main window has five input fields (name, student ID, course ID, total score) and several buttons (Add new record, Delete all, Search, Sort by name, Sort by ID, Sort by course, Sort by score)
    To add a new record, fill in all the input fields and click on the "Add new record" button.
    To delete all records, click on the "Delete all" button.
    To search for a record, fill in the input fields and click on the "Search" button.
    To sort the records, click on the appropriate button (Sort by name, Sort by ID, Sort by course, Sort by score).
    The records will be displayed in a TextArea on the main window.

## Functionality

    Add new record: The user can add a new student record by filling in the input fields of name, studentID, courseID, and totalScore, then clicking on the "Add New Record" button. The record will be written to the database.txt file, and will also be displayed on the TextArea.
    Search record: The user can search for a specific record by entering the studentID in the studentID field and clicking on the "Search" button. If the record is found, it will be displayed on the TextArea, otherwise, a message will be displayed saying that the record was not found.
    Delete record: The user can delete a specific record by entering the studentID in the studentID field and clicking on the "Delete" button. If the record is found and deleted, a message will be displayed saying that the record was deleted, otherwise, a message will be displayed saying that the record was not found.
    Delete all records: The user can delete all the records by clicking on the "Delete All" button. A message will be displayed saying that all the records were deleted.
    Sort records: The user can sort the records by clicking on the "Sort" button. The records will be sorted by name in alphabetical order and will be displayed on the TextArea.
    Display all records: The user can display all the records by clicking on the "Display All" button. The records will be read from the database.txt file and will be displayed on the TextArea.

## Usage

    Start the application by running the App class.
    Use the input fields to add, search, and delete records.
    Use the buttons to add, search, delete, sort, and display all records.
    The records will be displayed on the TextArea.

