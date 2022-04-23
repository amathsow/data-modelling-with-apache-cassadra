## **Data Modeling with Apache Cassandra**
-----------------------------------------------------------------------------------------------------------------------------------

In this project, I will build an ETL pipeline using Python with the focus on Apache Cassandra and how it is different from relational database data modeling.

Cassandra primary keys is made up of Partion Keys or Clustering Columns.Data with the same Primary Key will be overwritten. In Where conditions the Primary Key must be included and you can use Clustering Columns to order your data.

In Cassandra the denormalization process is a must, you cannot apply normalization like an RDBMS 
because you cannot use JOINs. More the denormalization process is done more the query will 
run faster, in fact, Cassandra has been optimized for fast writes not for fast reads. 

I will process the event_datafile_new.csv dataset to create a denormalized dataset


Using provided queries, I will model the data tables

Load the data into tables created in Apache Cassandra and run provided queries



## **Motivation**
-----------------------------------------------------------------------------------------------------------------------------------

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team at Sparkify whats to know what songs users are listening to. In order to analyze songs and user activity they need to query certain data, however, the data they currently have is is JSON format.



## **Files**
-----------------------------------------------------------------------------------------------------------------------------------

#### Project Structure

* event_data - The directory of CSV files partitioned by date

* Project_1B_ Project_Template.ipynb - It is a notebook that illustrates the project step by step

* event_datafile_new.csv - The aggregated CSV composed by all event_data files



## **Installation**
-----------------------------------------------------------------------------------------------------------------------------------
Cassandra instance needs to be up and running

Python and Jupyter Notebook must also be installed.


*A new terminal must be ran for any changes made to the py files and the kernel for the ipynb files should be restarted to exit the connection
