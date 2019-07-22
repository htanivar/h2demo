# h2demo
## Configuration Notes:

Add the following in **application.properties**
~~~~Add the following in **application.properties**

> spring.h2.console.enabled=true
  spring.datasource.url=jdbc:h2:mem:testdb
  spring.datasource.driverClassName=org.h2.Driver
  spring.datasource.username=sa
  spring.datasource.password=
  spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
  spring.h2.console.path=/h2-console
 ~~~~
  
  **How to Access the H2-console**
  
~~~~
http://localhost:port/h2-console
