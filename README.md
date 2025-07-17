
# University Management System

## Overview
The University Management System is a Java-based application designed to manage various aspects of a university, including students, teachers, courses, grades, lectures, and messaging. The system provides separate dashboards for administrators, teachers, and students, allowing each user type to perform relevant tasks efficiently.

## Features
- **Admin Dashboard:** Manage students, teachers, courses, and view system data.
- **Teacher Dashboard:** View and manage lectures, grades, and communicate with students.
- **Student Dashboard:** View courses, grades, lectures, and send/receive messages.
- **Authentication:** Secure login for different user roles (Admin, Teacher, Student).
- **Data Models:** Includes models for Student, Teacher, Course, Grade, Lecture, and Message.

## Technologies Used
- **Java** (Core language)
- **Java Swing** (for GUI)
- **Maven** (for project management)

## Project Structure
```
/university management system
├── pom.xml
├── src/
│   └── main/
│       └── java/
│           └── com/university/
│               ├── AdminDashboard.java
│               ├── LoginFrame.java
│               ├── Main.java
│               ├── StudentDashboard.java
│               ├── TeacherDashboard.java
│               ├── data/
│               └── model/
└── target/
```

## Getting Started
1. **Clone the repository** (if applicable):
   ```
   git clone <repository-url>
   ```
2. **Build the project using Maven:**
   ```
   mvn clean install
   ```
3. **Run the application:**
   - You can run the `Main` class from your IDE or using the following command:
     ```
     mvn exec:java -Dexec.mainClass="com.university.Main"
     ```

## Usage
- Launch the application and log in as Admin, Teacher, or Student.
- Use the respective dashboard to manage or view data.

## Notes
- The application uses Java Swing for the user interface.
- Demo data may be available for testing purposes.

## License
This project is for educational purposes. 