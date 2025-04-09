## Project Title: Financial Advisor Management System

### Project Description
The Financial Advisor Management System is designed to enhance the management of client portfolios and securities for financial advisors at Wells Fargo. This comprehensive system aims to streamline operations, improve efficiency, and provide a better experience for both advisors and clients. The project addresses the limitations of existing solutions by offering a scalable and efficient platform that can handle multiple financial advisors and their clients.

As a project analyst at Wells Fargo, I was responsible for creating this new system to assist financial advisors in managing their clients' portfolios. The project involved understanding requirements, designing a robust data model, and implementing it using Java Persistence API (JPA) within a Spring framework application.

### Installation Instructions
To set up the Financial Advisor Management System, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Prerequisites**:
   - Ensure you have Java 21 installed on your machine.
   - Install Maven for dependency management.

3. **Build the Project**:
   Use Maven to compile the project:
   ```bash
   mvn clean install
   ```

4. **Run the Application**:
   Start the application using the following command:
   ```bash
   mvn spring-boot:run
   ```

### Usage Examples
Once the application is running, you can interact with the system through its API endpoints. Here are some practical examples:

- **Create a New Advisor**:
   ```bash
   POST /advisors
   {
       "firstName": "John",
       "lastName": "Doe",
       "address": "123 Main St",
       "phone": "555-1234",
       "email": "john.doe@example.com"
   }
   ```

- **Get All Clients for an Advisor**:
   ```bash
   GET /advisors/{advisorId}/clients
   ```

- **Update a Client's Information**:
   ```bash
   PUT /clients/{clientId}
   {
       "firstName": "Jane",
       "lastName": "Doe",
       "address": "456 Elm St",
       "phone": "555-5678",
       "email": "jane.doe@example.com"
   }
   ```

### Technologies Used
- **Java 21**: The primary programming language used for development.
- **Spring Framework**: A powerful framework for building Java applications, particularly for web applications.
- **Java Persistence API (JPA)**: Used for object-relational mapping to manage database interactions.
- **Maven**: A build automation tool used for managing project dependencies.

### Key Learnings
- **Understanding of JPA**: Gained a solid understanding of JPA as an object-relational mapping tool, crucial for bridging Java objects and relational databases.
- **Data Modeling Skills**: Enhanced skills in designing data models and visualizing them through Entity Relationship Diagrams (ERDs), essential for effective database design.
- **Spring Framework Proficiency**: Became proficient in using the Spring framework for Java, widely used in enterprise applications.
- **Collaboration and Communication**: Learned the importance of clear communication and collaboration within a software development team, especially when gathering requirements and validating designs.

This project not only allowed me to apply my technical skills in Java and Spring but also provided valuable insights into the software development lifecycle. I am excited about the potential impact of this system on the efficiency of financial advisory services at Wells Fargo and look forward to further opportunities to contribute to innovative solutions in the financial technology space..

