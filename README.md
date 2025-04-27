# 🏥 Hotel Management System - Java Console App 🏨

Manage your hotel operations efficiently with this Java-based console application. Add patients, view patient lists, manage doctors, and book appointments seamlessly.

## ✨ Features

*   **Patient Management:**
    *   Add new patient records with name, age, and gender.
    *   View a comprehensive list of all registered patients.
*   **Doctor Management:**
    *   View a list of available doctors with their specializations.
*   **Appointment Booking:**
    *   Book appointments for patients with specific doctors on available dates.
    *   Check doctor availability before booking.
*   **User-Friendly Console Interface:**
    *   Simple and intuitive menu-driven interface for easy navigation.

## 🛠️ Technologies Used

*   **Java:** Core programming language
*   **JDBC:** For database connectivity.
*   **MySQL:** Database for storing hospital data.

## ⚙️ Setup Instructions

1.  **Prerequisites:**
    *   Java Development Kit (JDK) installed
    *   MySQL Database set up and running

2.  **Database Setup:**
    *   Create a database named `hospital` in your MySQL server.
    *   Create `doctors` and `patients` tables with appropriate columns like that used in code and used in code to function the project.
    *   Configure the MySQL connection details in the `HospitalManagementSystem.java` file:

        ```java
        private static final String url = "jdbc:mysql://127.0.0.1:100/hospital";
        private static final String username = "username";
        private static final String password = "password";
        ```

        **Note:** Update the `url`, `username`, and `password` with your MySQL configuration.

3.  **Clone the Repository:**

    ```bash
    git clone https://github.com/Shubhambhagat3226/Hotel_Management_System.git
    cd Hotel_Management_System
    ```

4.  **Compile the Code:**

    ```bash
    javac src/HospitalManagementSystem/*.java
    ```

5.  **Run the Application:**

    ```bash
    java HospitalManagementSystem/HospitalManagementSystem
    ```

## 📜 Usage

1.  Run the `HospitalManagementSystem` class.
2.  The application will display a menu with the following options:

    ```
    HOSPITAL MANAGEMENT SYSTEM
    1. Add Patient
    2. View Patients
    3. View Doctors
    4. Book Appointment
    5. Exit
    ```

3.  Enter the number corresponding to the action you want to perform.
4.  Follow the prompts to enter the required information.

## 📂 Project Structure

```
hotel_management_system/
├── Hospital management system.iml
└── src/
└── HospitalManagementSystem/
├── Doctor.java # Doctor management class
├── HospitalManagementSystem.java # Main class with menu
└── Patient.java # Patient management class
```
## 🧑‍💻 Author

*   Shubham Bhagat - [shubhambhagat3226](https://github.com/shubhambhagat3226)

Give this repository a ⭐ if you find it helpful!
