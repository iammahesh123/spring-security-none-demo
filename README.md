# Spring Security "none" Configuration Demo

This project demonstrates how to configure Spring Security with "none" authentication, where no authentication is required to access protected resources. It also showcases how to permit access to specific endpoints using the "permitAll" configuration.

## Overview

Spring Security provides flexible configuration options to control access to resources. In scenarios where authentication is not required or for certain public endpoints, you can configure Spring Security to use "none" authentication and permit access to those endpoints explicitly.

## Features

- Spring Security configured with "none" authentication
- Permit access to specific endpoints using "permitAll"
- Simple demo endpoints to illustrate configuration

## Project Structure

- `src/main/java`: Contains the Java source code for the Spring Boot application.
- `src/main/resources`: Contains configuration files and static resources.
- `pom.xml`: Maven project configuration file.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/iammahesh123/spring-security-none-demo.git
```
2. Navigate to the project directory:
 ```bash
  cd spring-security-csrf-demo
 ```
3. Build the project using Maven:
 ```bash
mvn clean package
 ```
4. Run the application:
```bash
mvn springboot:run
 ```
5. Access the application in your web browser: http://localhost:8080
6. Access the demo endpoints in your web browser or through an API client.
## Configuration
- `application.properties`: Contains application-specific configurations.
- `SecurityConfig.java`: Spring Security configuration class where "none" authentication and permitAll configurations are defined.
## Dependencies
- Java 8 or higher
- Spring Boot
- Spring Security
## Contributing
Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.
