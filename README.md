# Small Student Organizer

The Small Student Organizer  is a Windows Forms application developed in C#. This application allows users to manage student information, including adding new students and viewing student details by class.

## Features

- **Add Student**: Users can add new students to the system. Each student must have a name, last name, class, and ID. The class of the student is selected from a predefined list.
- **View Students by Class**: Users can view all students' IDs for a selected class. The class selection is done via a combo box.
- **View Student Details**: Users can view details of a specific student by selecting their ID from the list box. The details are displayed in labels.
- **Non-Resizable Forms**: The forms in the application are not resizable to ensure a consistent user experience.

## Technical Details

- **Dictionary Storage**: All student data is stored in a dictionary, where the key is the class of the student and the value is a list of student objects.
- **Encapsulation**: All fields in the `Student` class are encapsulated to adhere to good programming practices.
- **Event Handling**: The application uses event handling for updating the display based on user interactions, such as changing the selected class or student ID.

## Getting Started

### Prerequisites

- .NET Framework (version required by the application)
- Visual Studio or any compatible C# IDE

### Installation

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/Small-Student-Organizer.git
    ```

2. Open the project in Visual Studio or your preferred C# IDE.

3. Build the project to restore the required packages and dependencies.

### Running the Application

1. Start the application by running the `Form3` form. This is the main form where you can add new students or view existing students.

2. Use the `Add Student` button to open the `Form1` form, where you can enter the details of a new student and add them to the system.

3. Use the `See Students` button to open the `Form2` form, where you can select a class and view the list of student IDs for that class. Selecting an ID will display the student’s details.

## Project Structure

- **Form1**: Form for adding new students.
- **Form2**: Form for viewing students by class and their details.
- **Form3**: Main form with navigation options.
- **Student**: Class representing a student, with encapsulated fields.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or need further assistance, feel free to contact me at [typerstudent3@gmail.com].

---

Thank you for using the Small Student Organizer!
