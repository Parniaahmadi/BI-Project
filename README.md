The journey began with a deep dive into data connection and transformation. I harnessed the power of Power Query to build automated workflows for extracting, cleaning, transforming, and loading data.
This involved:
1- Data Extraction, Cleaning, and Shaping(applying transformations like grouping, pivoting, and merging queries to organize the data effectively), automation (creating repeatable workflows to streamline the data preparation process)
through these efforts, I ensured our data was accurate, consistent, and ready for analysis.


Second stage:
With clean data in hand, the next step was to build a strong relational data model. This stage focused on best practices in data modelling:
normalization (organizing data to reduce redundancy and improve integrity), structuring the data into fact and dimension tables, relationships (establishing primary and foreign key relationships, and configuring active and inactive relationships),
managing relationship cardinality and filter flow to ensure accurate data retrieval.
Building this model from the ground up laid the foundation for effective data analysis and reporting.
In this model, I ensured that each table had a clear and distinct role by leveraging relationships. Additionally, I organized dimension tables above the data tables to show filter flow "downstream".

![Screenshot 2024-04-27 112200](https://github.com/Parniaahmadi/BI-Project/assets/129201205/d47d9cbe-fbbe-4d34-9656-744008137b68)


Model Layouts: In next image, I've create custom views to show specific portions of models.

First picture, Shows the Sales model view

![Screenshot 2024-04-27 112230](https://github.com/Parniaahmadi/BI-Project/assets/129201205/1ae251ef-faba-43f1-8722-43df342be7f1)

On the Second picture, you will see Returns model view.

![Screenshot 2024-04-27 112244](https://github.com/Parniaahmadi/BI-Project/assets/129201205/f91f7d39-c11a-488a-95ef-20946f381b33)


The third stage was enhancing our data model with calculated fields using Data Analysis Expressions (DAX). This involved:
Creating Measures and Columns (developing calculated columns and measures to perform complex calculations), leveraging functions like CALCULATE, FILTER, and time intelligence patterns to add depth to our analysis.
These calculated fields empowered us to derive more meaningful insights from our data.
![image](https://github.com/Parniaahmadi/BI-Project/assets/129201205/3730a7f2-2e84-4445-b12d-83a2f8642c90)

![image](https://github.com/Parniaahmadi/BI-Project/assets/129201205/06f4b3bf-21cc-4c1e-9d9d-95dff1175987)

![image](https://github.com/Parniaahmadi/BI-Project/assets/129201205/71b96c6b-3aa5-4b6c-a83b-6ac135e764e3)

Created measure for 10 day rolling revenue

![image](https://github.com/Parniaahmadi/BI-Project/assets/129201205/6bb95bbe-45af-428e-9e5c-e84b63edcc74)


The final stage brought our data to life through visualization. Using Power BI, I designed interactive dashboards and reports:
applying best practices to create clear, effective visualizations, adding features like slicers, drillthroughs, and custom tooltips to enhance user experience. implementing role-based security to control data access.
These visualizations provided executives with real-time insights into sales metrics, operational KPIs, and financial benchmarks, streamlining data access and interpretation.

Created Dashboards for Revenue, Profit, Orders and Return rates for the top 10 products for the years 2021 and 2022. 
![image](https://github.com/Parniaahmadi/BI-Project/assets/129201205/0fbc150f-c9c9-466c-84f1-18ab14a5de07)

![image](https://github.com/Parniaahmadi/BI-Project/assets/129201205/42a6536d-8383-4a0f-a61f-9db5857247c5)

 Product details
 ![image](https://github.com/Parniaahmadi/BI-Project/assets/129201205/ab0752df-073e-4e40-a409-9e34499ee166)

 Customer details
 ![image](https://github.com/Parniaahmadi/BI-Project/assets/129201205/be7c8d41-14a7-469b-8b12-ddd2e00dfcb4)






