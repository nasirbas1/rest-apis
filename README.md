REST APIs using Spring 5, JPA, map struct

To run the project 
1.Install all the maven dependencies, run  mvn idea:idea in the terminal.
2.Compile & run the project.



The project uses in memory H2 database. To access
the same, go to "http://localhost:8080/h2-console/"
Click connect (Make sure the JDBC url is: "jdbc:h2:mem:testdb")

API-endpoints for fruit shop

1.Categories

[GET] /api/v1/categories => retrieves all categories
[GET] /api/v1/categories/{categoryName} => retrieves the category based on param passed

2.Customers

[GET] /api/v1/customers => retrieves all the customers
[GET] /api/v1/customers/{customerId} => retrieves specific customer
[POST]   /api/v1/customers => Request body[firstname, lastname] => creates new customer
[PUT]    /api/v1/customers/{customerId} => updates one customer based on Id
[PATCH]  /api/v1/customers/{customerId} => patches one customer based on Id
[DELETE] /api/v1/customers/{customerId} => deletes a customer based on Id

3.Vendors

[GET] /api/v1/vendors => retrieves all the vendors
[GET] /api/v1/vendors/{vendorId} => retrieves specific vendor
[POST]   /api/v1/vendors => Request body[name] => creates new vendor
[PUT]    /api/v1/vendors/{vendorId} => updates one vendor based on Id
[PATCH]  /api/v1/vendors/{vendorId} => patches one vendor based on Id
[DELETE] /api/v1/vendors/{vendorId} => deletes a vendor based on Id




