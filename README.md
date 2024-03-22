# Legislative Voting Data Warehouse for Local Councils, Regional Parliaments, and National Parliament

## Introduction
The project "Legislative Voting Data Warehouse for Local Councils, Regional Parliaments, and National Parliament" focuses on collecting, analyzing, and processing data on the voting behavior of legislators at various levels of government in Slovakia. The goal is to create a reliable source of information about legislators' decisions and voting patterns.

## Data Source
Data analysis includes information from the National Council of the Slovak Republic, city councils in Košice, and regional parliaments in Košice. Various sources were used to obtain data, such as websites and PDF files.

### Data Transformation
Data transformation involved the process of conversion and modification of data into a format suitable for storage and analysis in the database.
- National Council of the Slovak Republic: A web scraper was used to retrieve data from websites. The data were then converted into a structured format.
- City councils of Košice: Data were available in formats such as .csv and .xlsx on the open data websites of Košice, enabling easy extraction.
- Higher territorial unit of Košice: Data were obtained in PDF format, requiring the use of file converters, such as Adobe's service, to reformat them into CSV.

Data transformation also included enriching the data using information from the commercial and trade register, which was manually verified and recorded.

## Data Processing
After obtaining the data, the process involved processing and storing it in a database. The Azure SQL Database cloud service was used for data management and storage, with JetBrains' DataGrip database software used for data management and editing. After importing the data into the database, they underwent editing and normalization. The created star schema enabled reliable and efficient analysis and processing of the data.

## Information Package
The created information package ensures data consistency and enables analysis. The star schema provides efficient and reliable evaluation of legislators' votes and decisions.

## Outcome and Significance
The overall outcome of the project is the creation of a robust and reliable tool for analyzing legislators' votes at various levels of government in Slovakia. This project has the potential to provide valuable information for political analysis, decision-making, and transparency in government processes.

## Source code
If you want to know more about project, please contact me.

