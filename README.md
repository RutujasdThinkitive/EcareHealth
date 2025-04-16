# EcareHealth Automation Framework

This is an automation testing framework for the EcareHealth application. The framework is built using:
- Java
- Selenium WebDriver
- TestNG
- Maven

## Project Structure
- `src/main/java` - Contains the main framework code and page objects
- `src/test/java` - Contains test cases
- `Resources` - Contains test data files
- `Reports` - Contains test execution reports
- `driver` - Contains WebDriver executables
- `screenshots` - Contains test execution screenshots
- `TestData` - Contains test configuration files

## Setup
1. Clone the repository
2. Install Java JDK 8 or higher
3. Install Maven
4. Update the `config.properties` file with your test environment details
5. Run `mvn clean test` to execute the tests