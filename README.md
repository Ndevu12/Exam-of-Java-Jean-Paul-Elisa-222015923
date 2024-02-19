# Registration-Form-and-login-form-with-Java

# Jean Paul Elisa NIYOKWIZERWA 222015923

This project was developed as part of the Advanced Programming with Java model exam in BIT (Business information technology) Level 2 at University of Rwanda, Gikondo Campus. It focuses on creating a secure user registration and authentication system using Java and MySQL. 
The application consists of four main files: `SignUp.java`, `LogIn.java`, `HomePage.java`, and `DBConnection.java`.

## Project Structure

### 1. SignUp.java
- Manages user registration.
- Allows users to input their details for storage in the MySQL database.
- Implements secure password hashing for enhanced security.

### 2. LogIn.java
- Handles user authentication by verifying credentials against stored information in the database.
- Ensures a secure login process to prevent unauthorized access.

### 3. HomePage.java
- Represents the main application interface post successful login.
- Provides a user-friendly dashboard or landing page for authenticated users.

### 4. DBConnection.java
- Manages the connection to the MySQL database.
- Includes methods for executing queries and handling database-related operations.

## Skills Demonstrated

1. **Java Programming:**
   - Utilized core Java concepts for the implementation of registration and authentication logic.

2. **MySQL Database Interaction:**
   - Implemented database connectivity using JDBC in `DBConnection.java`.
   - Stored and retrieved user information from the MySQL database.

3. **Security Measures:**
   - Implemented password hashing in `SignUp.java` for secure storage of user credentials.
   - Ensured secure authentication in `LogIn.java` to prevent unauthorized access.

4. **User Interface:**
   - Designed a straightforward user interface for registration and login using Java GUI components.

5. **Code Organization:**
   - Demonstrated proper code organization by separating functionalities into distinct classes (`SignUp.java`, `LogIn.java`, `HomePage.java`, and `DBConnection.java`).

6. **Exception Handling:**
   - Implemented exception handling mechanisms to enhance the robustness of the application.

## Usage

1. **Database Setup:**
   - Ensure MySQL is installed and create a database for the application.
   - Update the database connection details in `DBConnection.java`.

2. **Compile and Run:**
   - Compile the Java files using `javac` and run the application.

3. **Testing:**
   - Test user registration and login functionalities using sample data.

## Dependencies

- MySQL database.
- Java Development Kit (JDK) version 8 or higher.

## Future Improvements

- Implement password recovery/reset functionality.
- Enhance the user interface for a more user-friendly experience.
- Add more robust error handling and logging.



## Contributing

We welcome and appreciate contributions from the community! If you would like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Description of changes'`.
4. Push your changes to your fork: `git push origin feature-name`.
5. Open a pull request to the `main` branch of this repository.

Thank you for considering contributing to this project! Together, we can make it even better.


## Conclusion

This project provided valuable experience in developing a secure and functional user authentication system using Java and MySQL. The skills gained include Java programming, database interaction, security implementation, and code organization. Future enhancements can further improve the project's features and usability.
