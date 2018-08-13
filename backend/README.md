# qrPay - Backend Module
App to support transactional QR codes for secure Payments


### Backend Module Tech Stack

- Java 1.8
- Spring Boot 1.5.x
- Maven
- Mysql

### Installation  

- Build back-end environment

        cd qrPay/backend
        mvn eclipse:eclipse (load build tools for Eclipse)
        mvn clean install

- DB Setup for back-end environment

        cd qrPay/backend/src/main/resources/application.properties
        spring.datasource.url=jdbc:mysql://localhost/<dbname>
        spring.datasource.username=<dbusername>
        spring.datasource.password=<dbpassword>


### Usage

- Run back-end server

        cd qrPay/backend
        mvn spring-boot:run
