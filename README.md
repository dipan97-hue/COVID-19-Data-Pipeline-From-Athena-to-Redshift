# Covid -19 ETL Pipeline from Athena to Redshift
-----
This repository contains a comprehensive data engineering project focused on COVID-19 data. Leveraging Amazon Web Services (AWS) tools such as Athena, Glue, S3, and Redshift, the project encompasses the entire data pipeline from querying raw COVID-19 data to building a relational data model in Redshift for analysis.
-----
The project include:

* Connectivity to AWS Athena for querying COVID-19 data.
* Python-based ETL (Extract, Transform, Load) jobs for processing data and saving results to AWS S3.
* ETL job setup and execution using AWS Glue for scalable data processing.
* Creation of tables on Amazon Redshift and copying processed data from S3 to Redshift for storage and analysis.

----

Small Snippet about how to connect to S3 bucket and create bucket has been presented in the redshift.ipynb file. 

Main file where the ETL transformation has been done is provided in Covid-19-ETL.ipynb file. 
------

