# StudentManagementSystem

- Project Overview  
- Features  
- Requirements  
- Installation  
- Running the Application  
- Folder Structure  
- Contributing  
- License  
- Contact  

# Student Registration System (JavaFX)

A comprehensive Student Registration System built using JavaFX. This application allows educational institutions to manage student records, course enrollments, and administrative tasks in a user-friendly desktop environment.

## Features

- Student registration: create, update, view, and delete student records
- Course management: add, edit, and remove courses
- Enrollment: enroll students to courses and manage enrollments
- Search & filter: easily search for students and courses
- Responsive JavaFX GUI
- Data persistence (using a database or file-based storage)
- Authentication for secure access (if implemented)
- Clean, modular codebase

## Requirements

- **Java JDK 11 or above**  
  (JavaFX is not bundled with JDK 11+, so you must install it separately)
- **JavaFX SDK** (Download from [GluonHQ](https://gluonhq.com/products/javafx/))
- **IDE** such as IntelliJ IDEA, Eclipse, or NetBeans (recommended)
- **Database**:  
  - For file-based storage: No additional setup is needed  
  - For database (e.g., MySQL, SQLite): Ensure the database server is running and connection credentials are set in the code/config

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Chinjehbrayan/student-registration-system-javafx.git
   cd student-registration-system-javafx
   ```

2. **Install JavaFX SDK**
   - Download JavaFX SDK from [GluonHQ](https://gluonhq.com/products/javafx/)
   - Extract it to a known location

3. **Configure your IDE intellij or any other**
   - Add JavaFX library to your project/module dependencies
   - Set VM options for JavaFX:
     ```
     --module-path /path/to/javafx-sdk-XX/lib --add-modules javafx.controls,javafx.fxml
     ```
     Replace `/path/to/javafx-sdk-XX` with the actual path to your JavaFX SDK

4. **Configure Database (if required)**
   - For MySQL/SQLite, create a database and update the connection details in the code (usually in a `DBConnector.java` or a configuration file)

## Running the Application

- **Via IDE**: Run the `Main.java` or the main application class.
- **Via Command Line**:
  ```bash
  javac --module-path /path/to/javafx-sdk-XX/lib --add-modules javafx.controls,javafx.fxml -d out src/**/*.java
  java --module-path /path/to/javafx-sdk-XX/lib --add-modules javafx.controls,javafx.fxml -cp out your.main.ClassName
  ```

## Folder Structure

```
student-registration-system-javafx/
├── src/
│   └── ...               # Java source files
├── resources/            # FXML, CSS, images, etc.
├── README.md
└── ...
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

For questions or suggestions, feel free to open an issue or contact the repository owner:

- GitHub: [Chinjehbrayan](https://github.com/Chinjehbrayan)
