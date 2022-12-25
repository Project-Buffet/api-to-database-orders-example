# api-to-database-orders-example
This integration takes a set of Orders from a Mock REST API and inserts them into a Database table. This project can be repurposed for any data type beyond just Orders. Be sure to clear the database table of Orders before moving the data.

This project requires creating a mock API to pass the data from. This is the site I use to create mock API endpoints: https://mockapi.io/projects

I've included a database SQL schema in the "dbSQLSchema" folder in src/main/resources which should allow you to easily create the database table required for this use case
