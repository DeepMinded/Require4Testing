# Require4Testing

Require4Testing is a web application designed to facilitate the organization and management of manual user testing. This project aims to streamline the process of creating, managing, and executing test cases for various requirements.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage Guidelines](#usage-guidelines)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create testable requirements.
- Manage test runs and assign test cases.
- Create test cases linked to specific requirements.
- Assign testers to test runs.
- Track test results and statuses.

## Technologies Used

- JavaServer Faces (JSF)
- Contexts and Dependency Injection (CDI)
- Java Persistence API (JPA) with Hibernate
- MySQL Database
- Maven for project management

## Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Require4Testing.git
   ```

2. Navigate to the project directory:
   ```
   cd Require4Testing
   ```

3. Ensure you have Maven installed. Build the project using:
   ```
   mvn clean install
   ```

4. Set up the MySQL database and configure the `persistence.xml` file located in `src/main/resources/META-INF/`.

5. Deploy the application on a compatible server (e.g., Apache Tomcat).

## Usage Guidelines

- Access the application through your web browser at `http://localhost:8080/Require4Testing`.
- Follow the on-screen instructions to create requirements, test cases, and manage test runs.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.