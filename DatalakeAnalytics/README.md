# Batch Analytics

## Batch Analytics with Data Lake Analytics Service

![Header Image](images/datalakeanalytics.png)

Process big data jobs in seconds with Azure Data Lake Analytics. There is no infrastructure to worry about because there are no servers, virtual machines, or clusters to wait for, manage, or tune. Instantly scale the processing power, measured in Azure Data Lake Analytics Units (AU), from one to thousands for each job. You only pay for the processing that you use per job.

U-SQL is a simple, expressive, and extensible language that allows you to write code once and have it automatically parallelized for the scale you need. Process petabytes of data for diverse workload categories such as querying, ETL, analytics, machine learning, machine translation, image processing, and sentiment analysis by leveraging existing libraries written in .NET languages, R, or Python.

In this lab Learn how to 

* use Data Lake Analytics to run big data analysis jobs that scale to massive data sets
* how to create and manage batch, real-time, and interactive analytics jobs, and 
* how to query using the U-SQL language

## Create Azure Data Lake Analytics Service

Create Data Lakae Analytics service to mine data stored in Data Lake Store.

Click on **Create a resource**

![Create Datalake Analytics Service](images/create_resource.png)

Click on **Data + Analytics**

![Create Datalake Analytics Service](images/dataanalytics.png)

Click on **Data Lake Analytics**

![Create Datalake Analytics Service](images/01_Create_Data_Lake_Analytics_Servicev2.png)

Pick the Data Lake Store where device telemetry data is being stored from Stream Analytics job

![Pick A Store](images/02_Create_Data_Lake_Pick_Storev2.png)

Use existing resource group and click on Create button

![Create Service](images/03_Create_Data_Lake_Analytics_Successv2.png)

## Create Job

Click on Open Synapse Studio

![Create Sample Data](images/image033.png)

Click on Ingest

![Create Sample Data](images/image034.png)

Click on Built-in copy task

![Create Sample Data](images/image035.png)

Click on New Connection

![Create Sample Data](images/image036.png)

Click on Next Dataset configuration

![Create Sample Data](images/image037.png)

Click on Next Destination

![Create Sample Data](images/image038.png)

Click on Next Destination data store 

![Create Sample Data](images/image040.png)

Click on Next Settings

![Create Sample Data](images/image041.png)

Click on Next Settings 

![Create Sample Data](images/image042.png)

Click on Next Finish 

![Create Sample Data](images/image043.png)




-------

References

https://github.com/MicrosoftLearning/mslearn-synapse/blob/master/Instructions/Labs/01-Explore-Azure-Synapse.md
![image](https://github.com/steve-cardenas/azureiotlabs/assets/120434396/8e07ad4c-b381-402e-8805-a49ee86b9dd2)




