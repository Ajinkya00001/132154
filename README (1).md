
# Kanban Assignment

This project is a Java-based application for managing Kanban tasks and user activities, utilizing **TestNG** for testing and **Maven** for build management. The project contains both implementation and test cases, covering functionalities such as user management, project creation, login, and more.

---

## 📂 Project Structure

### **1. `src/main/java`**
This folder contains the core implementation of the application:
- **`BaseTest/Test.java`**: Base setup for tests.
- **`pages`**: Contains page classes for different functionalities:
  - `CreateNewUser.java`
  - `LoginPage.java`
  - `LoginWithNewPassword.java`
  - `UserManagement.java`
  - `creatNewProject.java`
  - `failedLogin.java`
  - `manageProject.java`

### **2. `src/test/java`**
This folder contains the test cases for the application:
- **`tests`**: Test classes corresponding to the application pages:
  - `CreateNewUserTest.java`
  - `LoginPageTest.java`
  - `LoginWithNewPasswordTest.java`
  - `UserManagementTest.java`
  - `creatNewProjectTest.java`
  - `failLogin.java`
  - `testng.xml`: Configuration for running TestNG test suites.

### **3. Configuration Files**
- **`pom.xml`**: Maven configuration file for managing dependencies and build settings.
- **`TestNG.xml`**: TestNG configuration for running test suites.

### **4. `.settings`**
Contains IDE-specific settings:
- `org.eclipse.core.resources.prefs`
- `org.eclipse.jdt.core.prefs`

### **5. `target`**
Contains compiled files and build artifacts, along with Maven-specific metadata.

### **6. `test-output`**
Generated reports and logs from TestNG execution:
- HTML reports, XML results, and additional resources.

---

## 🚀 How to Run the Project

### **1. Prerequisites**
- Java Development Kit (JDK) 8 or higher
- Apache Maven 3.6+
- TestNG Plugin (if running tests in an IDE like Eclipse)

### **2. Build the Project**
Run the following command to build the project:
```bash
mvn clean install
```

### **3. Execute Tests**
Run the TestNG test suite:
```bash
mvn test
```

Alternatively, execute tests directly from the `TestNG.xml` file in your IDE.

### **4. View Test Reports**
After running tests, navigate to `test-output/index.html` to view the TestNG report in your browser.

---

## 🛠 Key Features
- **User Management**: Create, update, and manage users.
- **Project Management**: Create and manage projects.
- **Authentication**: Login functionality with test cases for successful and failed login attempts.
- **Automated Testing**: Comprehensive test suite using TestNG.

---

## 📜 Dependencies
The project uses the following dependencies (defined in `pom.xml`):
- **TestNG**: Testing framework.
- **Maven Compiler Plugin**: For compiling Java code.
- **Additional Libraries**: As per the project requirements.

---

## 📋 Contribution Guidelines
1. Fork the repository.
2. Create a new feature branch.
3. Commit changes and create a pull request.

---

## 📄 License
This project is licensed under [MIT License](LICENSE).
