# Data-Warehouse-for-FudgeInc-company

# FudgeInc has fudgeflix and fudgemart as service products. Fudgeflix is similar to Netflix that is streaming movies and Fudgemart is similar to Amazon retail, providing online 
# retail shop. So a datawarehouse needs to be created for both the product service. The datat profile for the servce line database is given in 
# IST722_Project_Fudgemart_Companies_data_profiling file. 

# A higher level overview for all the business line was identified and mention in High_Level_Dimensional_Modelling_Solution file.We decided to create data warehouse for sales
# business line for both the services. So the facts and dimension and its attributes were identified and mentioned in Detail_Dimensional_Modelling_Solution file. Attributes data 
# types, length, names etc. are all mentioned and described in Detail_Dimensional_Modelling file.

# Staging tables were created in MS-SQL using SSMS. The SQL query used is attached in Final_Query file. Using SSIS, data was extracted from databases of Fudgeflix and Fudgemart 
# and loaded into staging tables. Then the data was transfomed and then loaded into data warehouse using SSIS. 

# ETL process was carried out in SSIS tool. Whole ETL process is explained in ETL Process file. Multidimensional cube was created in SSAS. The star schema of implemented data warehouse is shown in Image file attached. 

# Using PowerBI, visualizations were made to analyze the sales of Fudgemart and Fudgeflix service line. This analysis were mentioned in the powerpoint presentation that is 
# attached. Along with analysis and visulaizations, recommendations were made in powerppoint presentatio to improve the sales of each service line. 
