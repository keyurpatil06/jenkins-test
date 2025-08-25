# My Maven Project

This is a simple Maven project that demonstrates the structure and functionality of a basic Java application.

## Project Structure

```
my-maven-project
├── src
│   ├── main
│   │   └── java
│   │       └── App.java
│   └── test
│       └── java
│           └── AppTest.java
├── pom.xml
└── README.md
```

## Description

- **App.java**: This is the main class of the application. It contains the `main` method which serves as the entry point for the application.
- **AppTest.java**: This class contains unit tests for the `App` class to ensure its functionality.
- **pom.xml**: This is the Maven configuration file that specifies project dependencies, build settings, and plugins required for the project.

## How to Build and Run

1. Ensure you have Maven installed on your machine.
2. Navigate to the project directory.
3. Run the following command to build the project:
   ```
   mvn clean install
   ```
4. To run the application, use:
   ```
   mvn exec:java -Dexec.mainClass="App"
   ```

## Running Tests

To run the tests, execute the following command:
```
mvn test
```

## License

This project is licensed under the MIT License.