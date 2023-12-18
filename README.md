# PostgreSQL database deployment with knowledge transfer from on-premises DBAs team using Microsoft Azure Database for PostgreSQL Servers.

![picture with the words Cloud Project and icons of the services used](https://miro.medium.com/v2/resize:fit:720/format:webp/0*HDCNqBpELpXMNMv5.jpg)

In another project based on a real-world scenario, I acted as a Cloud Specialist to show a team of on-premises DBAs how to provision a PostgreSQL database on Microsoft Azure.

I supported the deployment and showed the step-by-step to create the database service in Microsoft Azure. I shared how the connection to the database service in Azure worked,
what were the steps of creating a new database, a new schema, and a new table. Also, I instructed them how to insert new records and query data in the table.

![picture showing a graph of the solution architecture](https://miro.medium.com/v2/resize:fit:720/format:webp/0*pNreSKs_q2pMt6tM.jpg)

For the setup I used Azure Database for PostgreSQL. I created a new database on Azure using the console, creating a new user and password for remote access.
While the deploy was finishing, I downloaded pgAdmin, a open-source admin program for PostgreSQL databases. With the deploy done and the app instaled, I created a
access rule allowing my IP to access the newly created database. Using the credentials I previously created, I connected pgAdmin to the database, allowing quick and easy
management of the Azure-hosted database. I created a new schema and a new table for testing purposes. I ran a command trough pgAdmin to add a new line on the new table
and quickly executed a query to show the line, finishing the test. The process was very quick and showed how practical is to crate a new database on the cloud and how 
easy is to connect it to a on-premises database. Azure helps a lot, showing practical commands and critical information in easily glanceable places, allowing very
quick setups for demanding situations.
