## Banking Application
The Banking Application is a simple banking system that allows users to manage accounts, deposit money, withdraw money, transfer funds between accounts, and check the balance.

Built using Java, Spring Boot, and Thymeleaf, the application includes both back-end logic and a front-end UI.
## Technologies Used
 * FrontEnd: CSS, HTML, BootsStrap
 * BackEnd: Java, Spring Boot, RestFul API's
 * DataBase: MySQL (for storing user data)
 * JPA: Hibernate for database interaction
   
## Features
 * Amount or Money Deposit
 * Amount or Money WithDraw
 * Account to any Account Amount Transtion
 * Showing Bank Balance

## How to Run It
  ## 1. Repository
   * Clone the Repository:-'https://github.com/NARAYANA3399/Banking_Application'
   * Navigate to the Project folder.
   * Run the application using 'mvn Spring-boot:run'.
  ## 2. Set Up the Application
   * If using MySQL, update the database properties in 'src/main/resources/application.properties'.

      * spring.datasource.url=jdbc:mysql://localhost:3306/mvc
      * spring.datasource.username=root
      *  spring.datasource.password=password
      *  spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
      *  spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect
      *  spring.jpa.hibernate.ddl-auto=update 
      * spring.jpa.show-sql=true
     
  ## 3.Run the Application
   * Open the project in your IDE (e.g., IntelliJ or VS Code).
   * Run the BankingApplication.java class (which contains the @SpringBootApplication annotation).
   * The application should now be running at 'http://localhost:8080'.
  ## 4. Test the API Endpoints
   ## Use Browser or any API client to test the following endpoints:
   
   *  GET /bank/ - Bank Home Page

   * POST /bank/create - Create a new Account

   * POST /bank/deposit - Amount Deposit

   * POST /bank/withdraw - Amount WithDraw

   * POST /bank/transfer - Account To Account Amount transfer

   * GET /bank/balance - Account Balance


 ## SCREEN SHORT
 
  * Bank Home Page
![Screenshot 2025-04-10 161813](https://github.com/user-attachments/assets/6a8d16fb-1b6a-4adc-b8f8-669f2ee2c5b4)

  * Account Create & Amount Deposit
![Screenshot 2025-04-10 161813](https://github.com/user-attachments/assets/1f8e6f46-b4a4-415b-b14f-0f58b3e2eb89)

  * Amount WithDraw & Amount transfer
![Screenshot 2025-04-10 161829](https://github.com/user-attachments/assets/453afda0-de48-499b-838a-89377bf094be)

  * Amount transfer & Account Balance
![Screenshot 2025-04-10 165359](https://github.com/user-attachments/assets/4a5ea4d2-a9e6-493d-ac52-ebb32d94f295)


