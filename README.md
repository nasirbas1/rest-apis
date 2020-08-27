<strong>OVERVIEW</strong>\
REST APIs using Spring 5, JPA, map struct

To run the project 

<i>1.Install all the maven dependencies,
2.Compile & run the project.</i>


The project uses in memory <strong>H2 database</strong>

To access the same, go to <i><strong>http://localhost:8080/h2-console/</strong></i>

Click connect (Make sure the JDBC url is: <strong>jdbc:h2:mem:testdb</strong>)

API-endpoints for fruit shop

1.Categories

<strong>[GET]</strong> <i>/api/v1/categories</i> => retrieves all categories

<strong>[GET]</strong> <i>/api/v1/categories/{categoryName}</i> => retrieves the category based on param passed

2.Customers

<strong>[GET]</strong> <i>/api/v1/customers</i> => retrieves all the customers

<strong>[GET]</strong> <i>/api/v1/customers/{customerId}</i> => retrieves specific customer

<strong>[POST]</strong> <i>/api/v1/customers</i> => Request body[firstname, lastname] => creates new customer

<strong>[PUT]</strong> <i>/api/v1/customers/{customerId}</i> => updates one customer based on Id

<strong>[PATCH]</strong> <i>/api/v1/customers/{customerId}</i> => patches one customer based on Id

<strong>[DELETE]</strong> <i>/api/v1/customers/{customerId}</i> => deletes a customer based on Id

3.Vendors

<strong>[GET]</strong> <i>/api/v1/vendors</i> => retrieves all the vendors

<strong>[GET]</strong> <i>/api/v1/vendors/{vendorId}</i> => retrieves specific vendor

<strong>[POST]</strong> <i>/api/v1/vendors</i> => Request body[name] => creates new vendor

<strong>[PUT]</strong> <i>/api/v1/vendors/{vendorId}</i> => updates one vendor based on Id

<strong>[PATCH]</strong> <i>/api/v1/vendors/{vendorId}</i> => patches one vendor based on Id

<strong>[DELETE]</strong> <i>/api/v1/vendors/{vendorId}</i> => deletes a vendor based on Id




