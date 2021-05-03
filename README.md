# sql-project
Project Name:
Redfin Data Analyst Internship SQL Project

Project Objective:
For this project, I wanted to gather insights on how specific housing markets have been performing over the past four years based on Redfin real estate data. In order to solve this problem, I originally attempted to web scrape Redfin's search website for property listings based on their zipcode, and return information about pricing, location, bedroom/bathroom count, etc. 
However, due to Redfin not having an API and making it difficult for people to scrape their data, I instead resorted to utilizing their public real estate data that is updated on a weekly basis. From this dataset, I gathered insights on the California, Texas, and New York housing markets between 2017-2020.

Job Description:
Redfin is an online real estate brokerage company, similar to Zillow in that the company connects potential residential property buyers with real estate agents and sellers. The Data Analyst Internship focused on gathering insights for the company, mostly on an internal level, but also related to external data like the housing market. I chose this position because of my interest in real estate and the housing market, and its connection to using SQL and Python, which are two programming languages that are essential to data analytics, and I strive to keep improving my skills in both. This project is related to the job posting because I have exemplified my technical skills revolving around Python, SQL, and data analysis in general, as well as the fact that it is an analysis of the housing market using Redfin data, which I believe would be very applicable to the work at hand as a Redfin intern.

Data:
The data used in this project was sourced by Redfin, as well as additional census data to compare median household income prices across county regions in the US. The Redfin data was initially downloaded as a tsv file containing hundreds of thousands of rows (if not millions) of data for thousands of regions in the US over the past 4 years. Due to the limitations of my computer, I cut and reduced this data down to three states: California, Texas, and New York, and I also left out many of the real estate market measurements I deemed unnecessary for my analysis.

Notebooks:
Data Collection
https://github.com/theohargis/sql-project/blob/e81b3da273788a4ed0dcb6700fd7fba07a146746/data_collection_PUBLIC.ipynb
This notebook illustrates the process of connecting the Redfin tsv file to my SQL database. Additionally, the notebook shows the web scraping process, which was cut short due to being blacklisted from making requests to the Redfin search site.

SQL Analysis
https://github.com/theohargis/sql-project/blob/e81b3da273788a4ed0dcb6700fd7fba07a146746/sql_analysis_PUBLIC.ipynb
This notebook contains all of my SQL analysis queries, including exploratory queries I used to gain an in-depth understanding of the data I was working with, and to create VIEWs to query from more quickly. In the notebook, I present the primary question that I was looking to answer using the data, as well as two related sub questions. I also included business justifications and recommendations to Redfin based off of my analyses.

Future Improvements:
For future improvements, I would really like to have the opportunity to attempt web scraping again with Redfin as my program works well, and could generate valuable insights. As an alternative, if Redfin were to develop a public API, this would make the data gathering process much easier. Additionally, in terms of the data I used from the Redfin TSV file, there were some issues with data types that made calculations difficult to carry out, like integers being labeled as varchars. If I had more time, I would iron out those details and adjust the data types appropriately. Finally, while I know I was working with large datasets, I still think that there is plenty of room for improvement in terms of the efficiency of my SQL queries. A major future imrpvoement I would want to make is streamlining the queries to improve their speed.

Thanks!

