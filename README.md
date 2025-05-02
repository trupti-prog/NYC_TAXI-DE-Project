# NYC_TAXI-DE-Project

To create end-to-end data solutions by dynamically pulling the NYC Taxi data from the website.

**1) Problem**

Building pipelines with automated solution within Data Factory.

**2) Data**

The data we're using is from Taxi Trip Record. I have uploaded raw DBC files (gold_notebook and silver_notebook).

**3) About**

'NYC Taxi' is a DE project to deliver data solutions to just automate everything instead of manually uploading the files. It mainly focuses on building dynamic pipelines and using Medallion Architecture. We used API connection and stored our data in Parquet Format in the Bronze Layer. Then, we pulled this data and performed PySpark transformations and stored our data in Parquet format in the Silver Layer, then we read our data from silver layer and created Delta tables i.e, Versioning and Time Travel. Established connection and took care of security, because we used managed identities to read & write the data. In the end, we created the connection with PowerBI through databricks.
