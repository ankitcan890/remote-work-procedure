# Portfolio Project: UCW Remote Work Procedure #

**Project Title: UCW Find Remote Work Score of the Faculty** 

**Used Descriptive Analysis**

# Objective:

The main goal of this project is to develop and execute a fortified, effective, and expandable data analytics platform utilizing AWS services to evaluate the performance of faculty members engaged in remote work, using a sample dataset. The objective is to assess the performance of faculty members as remote work employees by utilizing sample data, focusing on data protection, governance, monitoring, and visualization.<br>

# Dataset:
A evaluation of the datasets was conducted using the sample work productivity excel file data and sample work availability csv file data.

# Methodology:
**Data Storage Design:**

Use AWS S3 to create three folders: curated, landing, and raw..<br>
Store extracted contract data in the landing folder for analysis..<br>

# Data Preparation:

Use AWS Glue Data Brew to prepare the dataset..<br>
Modify the schema for accurate data types and save processed data in a tabular format..<br>

**Create datasets:** 

hr-remoteworkprocedure-employeeproductivity-ankitkumar and hr-remoteworkprocedure-workhouravailiblity-ankitkumar

# Data Ingestion:

Standardize data using AWS Glue Data Brew by addressing missing values and storing standardized data in the raw folder..<br>

# Data Pipeline Design:

Use AWS S3 for data storage.<br>
Implement schema modifications to remove unnecessary columns.<br>
Use union operations to combine data from different tables.<br>
Perform aggregation to calculate values for the specified bid types.<br>
Store the final results in the curated folder in S3.<br>

<img src="https://ankitcan890.github.io/remote-work-procedure/ETL_UCW.png">

# Data Protection:

Use AWS Key Management Service (KMS) to create a symmetric key named "hr-remoteworkprocedure-dataset2-ankit" for encryption and decryption.<br>
Configure default encryption for the S3 bucket to ensure data protection.<br>

# Data Governance:

Utilise AWS Glue to create data pipelines for the ETL named "HR-Rwp-QRPR-Ankit".<br>
Use Canadian examples to implement detection techniques for identifying questionable data.<br>
Employ data filtering techniques to apply specified criteria and remove superfluous columns to achieve a pristine dataset.<br>

<img src="https://ankitcan890.github.io/remote-work-procedure/Gov.png">

# Data Monitoring:

Set up Amazon CloudWatch dashboards (e.g., "hr-remoteworkprocedure-dashboard-ankit") for monitoring costs and data usage.<br>
Implement alarms using CloudWatch to notify when thresholds are exceeded.<br>
Use CloudTrail to record user activities and modifications within the system.<br>

# Data Analysis: 

Create databases and tables (e.g., "hr_remote_work_procedure_table5_ankit") for storing and querying contract data.<br>
Perform SQL queries to retrieve and analyze the data for insights.<br>

# Data Visualization:

Graphically represent the remote work score of each professor by their respective professor ID.<br>
Upload findings to web servers for remote retrieval and dissemination.<br>

# Data Publishing: 

Publish findings using a general server and a web server for accessibility.<br>

# Tools and Technologies:

Data Storage: AWS S3<br>
Data Preparation: AWS Glue Data Brew<br>
Data Protection: AWS KMS<br>
Data Governance: AWS Glue, S3<br>
Data Monitoring: Amazon CloudWatch, CloudTrail<br>
Data Analysis: SQL (within AWS)<br>
Visualization: Graphs generated from analyzed data<br>

# Deliverables:

A secure AWS S3 storage design with data encryption enabled.<br>
Standardized datasets in the curated folder ready for analysis.<br>
CloudWatch dashboard and alarms for monitoring.<br>
Visual representations of the analysis results.<br>
Published data accessible on web servers.<br>

# Result:

<img src="https://ankitcan890.github.io/remote-work-procedure/screenshot_WS.png">

**Timeline:**

The expected completion time for this project is approximately 8-10 weeks, including phases for data storage setup, governance implementation, monitoring configuration, and final analysis.


