# Power_BI_Virtual_Case_Experience__Task_3

This is the last task in the Virtual case experience with PwC. Find previous tasks and more context here.    
In this task, I’m asked to;   

•	Define relevant KPIs in hiring, promotion, performance and turnover, and create a visualization     
•	Write what you think some root causes of their slow progress might be       

The above tasks were requested by the HR team. They’re looking for insights for improving gender balance in the executive level as they are highly into diversity and inclusion.     

The database contained 5 tables, namely; backing 1, backing 2, backing 3, backing 4 and Pharm group AG.       

## Data Cleaning;    

As I went through the different tables, I saw that there were very obvious differences between the tables.    
Also, no data dictionary was provided to aid my understanding of what the columns were. However, some columns even tables seem irrelevant. I dropped all the tables except the Pharm group AG table.      

The table had 500 rows and 32 columns. These columns were;     

_Employee ID, Gender, Job Level after FY20 promotions, New hire FY20?, FY20 Performance Rating, Promotion in FY21?, In base group for Promotion FY21, Target hire balance, FY20 leaver?, In base group for turnover FY20, Department @01.07.2020, Leaver FY, Job Level after FY21 promotions, Last Department in FY20, FTE group, Time type, Department & JL group PRA status, Department & JL group for PRA	Job Level group PRA status, Job Level group for PRA, Time in Job Level @01.07.2020, Job Level before FY20 promotions, Promotion in FY20?, FY19 Performance Rating	Age group, Age @01.07.2020, Nationality 1, Region group: nationality 1, Broad region group: nationality 1, Last hire date, Years since last hire, Rand._     

The aforementioned columns in bold contained nulls. These nulls were as a result of the number of leavers and new hires in the company, therefore I didn’t drop any.     
## Data Transformation;      

I replaced all Y’s and N’s with Yes’s and No’s in New hire FY20, In base group for turnover FY20 and Promotion in FY20.       
I extracted the years from the Last hire date column to determine how hiring has gone over the years.    

_No data modeling was required as the other tables were dropped._       

## Analysis and Visualization;     
 
To get insights on hiring, performance and turnover, and promotion I queried the dataset with the following questions;       

1.	What are the demographics of the employees (this included gender, leavers, countries, employment type, age group, department and countries)?         
2.	Which gender was mostly hired over the years?          
3.	What was the hiring percentage?         
4.	How was the company distributed by employment type and gender?         
5.	Did employment type affect performance rating?          
6.	How many people were selected for promotion? How many were promoted?          
7.	What were the promotion percentage between gender?          
8.	What gender more promoted in the Executive level and other levels?        

The Company's demographics shows the following; There are 295 males and 205 females, out of which 47 have left the company. The company is mostly populated by employees of the full time employment type. Most employees fall within age 20 and age 39. It is also interesting to see that there are employees who are above 60. It turns out that they are only males and 2 out of the 4 are in the executive team.            

Operations is the largest department, after which is the Internal Services. It shows that all the departments have more males than females.        
PhoneNow is operational in 22 countries. As expected, it's Switzerland headquarters holds more than half of all her employees, The other large chunk is distributed across the Europe region and on the top of that region are countries like France, Germany, Italy, United Kingdom, Spain.          
The gender disparity in most of these countries are glaring. In her headquarters, there are 169 males and only 95 females. France which is the second largest office has 59 males and only 36 females.       

Over the years, there was an evident gender gap when it came to hiring. This was very prominent in 2015. However, there have been noticeable changes in the last 3 years. More women were hired in 2018 and 2020.        
The hiring percentage in 2020 was mild but of course relevant.        

Earlier we noticed that there are more full-time employees than not. Most of them are males and just 2 males work as part-time employees, On the other hand, 33 females are part-time employees.           
Most employees, both male and female were given the rating of 3 in FY19. This is not the same case in the next fiscal year, FY20. More employees have a rating of 2. However, there was a subtle increase in the highest rating, 5 females and 2 males were rated at 4.      
Interact with the dashboard to see how employment type affect performance rating.       

A total of 376 persons were selected for promotion in FY21, out of which 228 were males and 148 were females. Only 10.2% of the entire population were promoted; 6.6% male, 3.6% female.        
This is little increase from the previous year, were only 7.2% were promoted; 5.6% male, 1.6% female.        
The largest and lowest job level of employees are junior managers, most of which are females. Other job levels have more males.         
As the job level increases, the number of female employees decreases. This is especially evident in level 1 and level 2 for executives and directors respectively.     

Currently, the executive level is occupied with 16 males and only 3 females. This is uneven.      

Root Causes and Recommendations;       

The HR team has hired more males than females over the years. The team should continue to look into recruiting more females.        
There was an uneven selection for promotion. An equal number of both male and female should be initially selected for promotion, it will make the final selection process less biased.




