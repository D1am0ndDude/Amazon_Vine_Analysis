# Amazon_Vine_Analysis

ETL and Meta-Analysis of Amazon Vine reviews with AWS, SQL, PySpark, and Google Colab

# Overview

The purpose of this project was to conduct a meta-analysis of Amazon Reviews. It was to analyze reviews produced as part of the Amazon Vine program, where select members of Amazon's reviewer community are compensated to review sample products. 
Out of the 50 datasets of product categories available to chose from, I chose to analyze reviews in the Pet category - requiring experience and knowledge to effectively review. The initial ETL portion of the project was conducted, as prescribed, using AWS, postgresql, and PySpark in Google Colab. The data analysis segment was conducted using PySpark and Google Colab.

# Results

# Deliverable 1

1. I chose the Amazon Video Game reveiw link provided to me, and created a DataFrame with that. 
2. Created a Database with Amazon RDS.
3. Created a new Database in PgAdmin and created an Amazon RDS Server.
4. Used the .SGL File to load in 4 Tables 
![image](https://user-images.githubusercontent.com/46943357/208265796-7e0d435d-cccc-4bb7-9ab0-2e838d921e17.png)

5. Created Four New Dataframes by using the .groupby() function in Google Colab. As the Following Images show:

![image](https://user-images.githubusercontent.com/46943357/208265881-ab954605-6ce1-44cb-9f3c-2a70318c7c85.png)

![image](https://user-images.githubusercontent.com/46943357/208265857-5427dfbb-4626-4f26-b13b-3a8f89c138e8.png)

![image](https://user-images.githubusercontent.com/46943357/208265867-8241be72-cc94-42ef-a1e8-48781b053116.png)

![image](https://user-images.githubusercontent.com/46943357/208265873-b34fd7b1-39c8-401d-b16e-e4e99ca8a009.png)

6. I linked Google Colab to the PGAdmin server and loaded in all the previously shown tables. As the following image shows.

![image](https://user-images.githubusercontent.com/46943357/208265919-79ed542f-0ea9-4f77-9e96-89e783754024.png)
