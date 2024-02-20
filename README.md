# Retail-Data-Analysis-Project-
/*This Retail Data Analysis project aims to leverage data-driven insights to enhance decision-making processes within the retail sector. By employing advanced analytics techniques, we intend to extract valuable patterns, trends, and actionable information from diverse retail datasets.*/

/*Tools used for this project are : Amazon Web Services ( Aws) , MySQL Workbench(ER diagram) , Snowflake(Sql) , Python(Automation) , Power-bi(visualization) .

🔷 AWS: Created an AWS S3 bucket and uploaded raw files into it .
       🔸Implemented secure access controls to the bucket, ensuring data confidentiality.
       🔸Enabled user-specific folders and data , upload capabilities for seamless data management.
       🔸Created Roles for the Users and Applied policies To the roles .

🔷SNOWFLAKE : 
       🔸Created tables and established a connection with AWS S3 for data integration. 
       🔸Configured Snowflake's storage integration , created Csv File Format , created External Stage 
        and created pipe to automate data ingestion. Set up a snowpipe to continuously ingest and 
        update data from the external stage.
      🔸Created a master table and implemented key performance indicators (KPIs) using cleaned 
        data .
      🔸performed exploratory data analysis .

🔷MySQL Workbench: 
      🔸Created the same tables in MySQL workbench and created an ER diagram .

🔷PYTHON ::  
      🔸Established a connection between Snowflake and Jupyter Notebook.
      🔸Performed data cleaning, modification, and conducted minor exploratory data analysis.  
      🔸Stored the cleaned data back into Snowflake for further analysis.

🔷JUPYTER_LAB : 
      🔸Utilized jupyter_scheduler and jupyterlab-scheduler for automation and scheduled refreshes.

🔷 POWER-BI : 🔸Connected Snowflake's clean data, master table, and KPIs to Power BI seamlessly. 
      🔸Leveraged the power of Power BI's features, such as data analysis expressions (DAX),measures, and parameters, to create an intuitive and insightful dashboard .
      🔸Publish the Report in the Power bi Service .*/
