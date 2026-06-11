# NEFU_ICEC

**My First Website Project**

A web application showcasing the Information and Computer Engineering College of Northeast Forestry University (NEFU), built with Java technologies.

## 📋 Project Overview

This is an educational web project that demonstrates a website for the Northeast Forestry University's Information and Computer Engineering College (NEFU_ICEC). The project implements modern web development practices using Java-based technologies and includes request filtering capabilities.

**Language:** Java  
**License:** MIT  
**Status:** Completed (Last updated: June 2022)

## 🛠 Technology Stack

- **Backend Framework:** Java Servlet/JSP
- **Build Tool:** Maven
- **Database:** MySQL
- **Web Server:** Supports servlet containers (Tomcat, etc.)
- **JDK Version:** Java 11+

### Key Dependencies

- **Servlet API:** `javax.servlet-api` (v4.0.1)
- **Apache Tag Libraries:** Standard spec and implementation (v1.2.5)
- **MySQL Connector:** `mysql-connector-java` (v8.0.21)
- **JSP Tag Support:** Apache TagLibs Standard

## 📂 Project Structure

```
NEFU_ICEC/
├── README.md
├── LICENSE
├── pom.xml
└── src/
    └── [Java source code and web resources]
```

## ✨ Features

- **Dynamic Web Pages:** Built with JSP (JavaServer Pages) for dynamic content rendering
- **Servlet Controllers:** Server-side request handling using Servlets
- **Request Filtering:** Custom filters implemented for request preprocessing and validation
- **Database Integration:** MySQL database connectivity for data persistence
- **College Information Display:** Showcase of NEFU's Information and Computer Engineering College details

## 🚀 Getting Started

### Prerequisites

- Java Development Kit (JDK) 11 or higher
- Maven 3.6+
- MySQL Server
- Servlet container (Apache Tomcat or similar)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/liu-shiqiang/NEFU_ICEC.git
   cd NEFU_ICEC
   ```

2. **Build the project:**
   ```bash
   mvn clean package
   ```

3. **Deploy the WAR file:**
   - Copy the generated `.war` file from the `target/` directory to your servlet container's webapps directory
   - Or deploy directly through your container's deployment interface

4. **Configure database:**
   - Update database connection settings in your configuration files
   - Ensure MySQL is running and the database is initialized

5. **Start the server:**
   - Start your servlet container (e.g., Tomcat)
   - Access the application at `http://localhost:8080/nefu_icec` (adjust port/context path as needed)

## 📦 Build & Deployment

### Building with Maven

```bash
# Clean and compile
mvn clean compile

# Run tests
mvn test

# Create WAR package
mvn package

# Full build lifecycle
mvn clean install
```

The compiled WAR file will be generated in the `target/` directory and can be deployed to any servlet container.

## 🔍 Key Components

### Request Filtering
The project utilizes servlet filters for:
- Request validation
- Security checks
- Request/response preprocessing
- Character encoding management

### JSP & Servlet Architecture
- **Servlets:** Handle business logic and request processing
- **JSP Pages:** Render dynamic content and user interfaces
- **Tag Libraries:** Apache Standard Tag Library for simplified JSP development

### Database Layer
- MySQL integration for persistent data storage
- College information and institutional data management

## 📝 Notes for Developers

- This is an educational project created to learn Java web development fundamentals
- The architecture demonstrates traditional JSP/Servlet patterns
- Modern applications would typically use frameworks like Spring, Spring Boot, or Jakarta EE
- The project serves as a good reference for learning servlet filters and JSP basics

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Liu Shiqiang**  
GitHub: [@liu-shiqiang](https://github.com/liu-shiqiang)

## 🤝 Contributing

As this is primarily an educational project, contributions are welcome. Please feel free to:
- Report issues
- Suggest improvements
- Submit pull requests

## 📚 Additional Resources

- [Java Servlet Documentation](https://docs.oracle.com/cd/E17802_01/products/products/servlet/index.html)
- [Apache Tomcat Guide](https://tomcat.apache.org/)
- [MySQL Documentation](https://dev.mysql.com/doc/)
- [Maven Documentation](https://maven.apache.org/guides/)

---

**Last Updated:** June 2022  
**Project Created:** January 2022
