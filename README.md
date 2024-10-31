# WebService Project

![Java](https://img.shields.io/badge/Java-17-blue)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.0-brightgreen)
![Maven](https://img.shields.io/badge/Maven-3.8.4-orange)

## Overview

Welcome to the WebService Project! This project is a RESTful web service built with Java, Spring Boot, and Jersey. It provides a comprehensive API for managing bank accounts (`Compte`).

## Demo Video

Watch the demo video below to see the project in action:

[JSON Demo Video](https://github.com/ayoub-sahraoui/spring-web-service/blob/main/json-api.mp4)

## Features

- **RESTful API**: CRUD operations for bank accounts.
- **MediaType Support**: JSON and XML.
- **Spring Boot Integration**: Leverages Spring Boot for easy setup and configuration.
- **Jersey Integration**: Uses Jersey for RESTful web services.
- **H2 Database**: In-memory database for development and testing.
- **Lombok**: Simplifies Java code with annotations.

## Getting Started

### Prerequisites

- Java 17
- Maven 3.8.4 or higher

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/ayoub-sahraoui/webservice.git
    cd webservice
    ```

2. **Build the project**:
    ```sh
    mvn clean install
    ```

3. **Run the application**:
    ```sh
    mvn spring-boot:run
    ```

### API Endpoints

- **Get Account by ID**: `GET /banque/comptes/{id}`
- **Get All Accounts**: `GET /banque/comptes`
- **Create Account**: `POST /banque/comptes`
- **Update Account**: `PUT /banque/comptes/{id}`
- **Delete Account**: `DELETE /banque/comptes/{id}`

### Example Requests

- **Get Account by ID**:
    ```sh
    curl -X GET "http://localhost:8080/banque/comptes/1" -H "accept: application/json"
    ```

- **Create Account**:
    ```sh
    curl -X POST "http://localhost:8080/banque/comptes" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"name\": \"John Doe\", \"balance\": 1000.0 }"
    ```

## Technologies Used

- **Java 17**
- **Spring Boot**
- **Jersey**
- **Maven**
- **H2 Database**
- **Lombok**

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please contact [ayoub-sahraoui](https://github.com/ayoub-sahraoui).

---

Happy coding! 🚀