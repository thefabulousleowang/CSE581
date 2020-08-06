# CSE581
Database Projects


Project 2: Amazon Competitor Database

In this project, you will design, implement, and test a database for an Amazon competitor/clone. In your design, you will need to determine
  a) necessary information to store (using second page as suggestions)
  b) an E/R diagram to construct (using MS Visio or any similar tool)
  c) business reports to produce (using at least four views)
  d) business logic to incorporate into the design (using several triggers and constraints)
  e) security levels to establish (using scripts for password assignments, roles and encryptions)
  f) performance and efficiency improvements to apply (using at least four stored procedures and four functions)
  g) regular business transactions (using at least four transactions)

In your implementation, you will need to
  a) determine the tables, columns, primary keys, datatypes, nullabilities, and relationships.
  b) normalize your design into its 3rd Normal Form.
  c) address potential integrity and security issues.

In your testing, you will need to
  a) populate your database with test data (about 10 rows in each table)
  b) produce about five reports (please use also your views)
  c) demonstrate its reliability through several complex scenarios
  d) perform several transactions like customer purchasing goods from the company, company gets goods from the supplier, customers leave reviews for the supplier, customer perform returns, etc.

Business Problem:
Your job is to create a database for an Amazon competitor. This database is to contain the following suggested information but more shall be added as you deem necessary. Please note that each order has a single shipping address, and can contain multiple products from one or more warehouses. Multiple warehouses may have the same product and the originating warehouse for a shipment is chosen based on the shipping cost, which can be determined by the zip codes of the originating warehouse and the shipping address. Suppliers may also have multiple products in various warehouses.
