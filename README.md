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

# Deliverable 2

To start off with, I filtered the available reviews to just those with more than 20 votes, and those which were more than 50% "helpful."

Reviews with 20+ Votes:
![image](https://user-images.githubusercontent.com/46943357/208266018-95c136f9-64e6-4866-8498-01ec9144e078.png)

The 50% that was helpful:
![image](https://user-images.githubusercontent.com/46943357/208266043-51d5899f-3fab-45e5-9870-0cf96fcc2e61.png)

Calculations were made from this filtered dataset to address the following questions:

* How many paid reviews were there? 94
![image](https://user-images.githubusercontent.com/46943357/208266160-5d9ac9bd-5dfb-4dbc-b697-7a1fc0155154.png)

* How many unpaid reviews were there? 40,471
![image](https://user-images.githubusercontent.com/46943357/208266179-8845b407-294c-4321-a01e-330da4f02f37.png)

* How many paid five star reviews? 48
![image](https://user-images.githubusercontent.com/46943357/208266200-1d3d9fb3-2cdd-4304-95bb-68cf157078dc.png)

* How many unpaid five star reviews? 15,663
![image](https://user-images.githubusercontent.com/46943357/208266227-4fd2c6a8-ab8a-401f-9ce2-5685fde41441.png)

* The percentage of Paid 5 star reviews 51.063%
![image](https://user-images.githubusercontent.com/46943357/208266272-49dc4822-26f4-485e-bf19-78c62ca00466.png)

* The percentage of Unpaid 5 star reviews 38.701%
![image](https://user-images.githubusercontent.com/46943357/208266295-125a41f6-d611-414b-a7dd-dd09646513ee.png)

## Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

