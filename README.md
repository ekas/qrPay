# qrPay
App to support transactional QR codes for secure Payments


### Main technology stack

- Java 1.8
- Spring Boot 1.5.x
- Maven
- Mysql
- vueJS 2.5.x

### Preparation

- Please must install Java 1.8  or even higher version
- install Node.js / NPM
- Clone Repository

        git clone https://github.com/ekas/qrPay.git
        cd qrPay

### Installation  
        
- Build front-end environment

        cd qrPay/frontend
        npm install

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

- Run Front-end Web Page

        cd qrPay/frontend
        npm run serve
