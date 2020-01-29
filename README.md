# DataManagement2

The guidlines for the project are as under

Step 1 Deducing the question

The various data dimensions are indentified on the dataset walmart.csv for which it had to be cleaned. Correspondingly different analytics questions are then being formulated which can be seen in the pdf "_Rishabh_Garg.pdf"

Step 2 ETL Workflow

The ETL workflow is performed using the Talend Data integration software and python. The dataset is cleaned for different dimensions using various components of the talend data integration software. Star schema is made on the cleaned dataset. This star schema is then pushed into MySql database. Using python the data is retrieved from different tables for further analysis. The entire project is available in the file "talend.project" and "MySqlToPython.pynb"

Step 3 Data Analytics

The data analytics is done using python where a logical connection with the MySql Database is performed using python and further analysis is done using different statistical models in the file "MySqlToPython.pynb"
