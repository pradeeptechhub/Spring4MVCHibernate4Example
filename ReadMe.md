WORKING
http://websystique.com/springmvc/spring-4-mvc-and-hibernate4-integration-example-using-annotations/

Check:
http://websystique.com/spring-security/secure-spring-rest-api-using-oauth2/

Step 7: Create Schema in database

CREATE TABLE MY_EMPLOYEE(
    id INT NOT NULL auto_increment, 
    name VARCHAR(50) NOT NULL,
    joining_date DATE NOT NULL,
    salary DOUBLE NOT NULL,
    ssn VARCHAR(30) NOT NULL UNIQUE,
    PRIMARY KEY (id)
);