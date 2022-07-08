# Data_Analysis_Project
Build a powerful dashboard using Power BI , which will give the revenue number , sales quantity number and track the revenue trends.

![sales_insight_dashboard_pic](https://user-images.githubusercontent.com/29626511/177542259-6c54b76d-c823-4e0c-9add-da1607ef44f3.JPG)

### Why we need to Data Analysis ?
Data Analysis is important because it makes studying data a lot simpler and more accurate.

### What does Power BI does?
Microsoft Power BI is used to find insights within an organization's data. Power BI can help connect disparate data sets, transform and clean the data into a data model and create charts or graphs to provide visuals of the data.

#### Problem Statement - 
In this I have chosen sales data of a manufacturing company . The problem the company is facing is that it have  sales region spread across the nation and each region is headed by a manager . Whenever top executive of the company ask for sales data of a region , the manager gives sugar coated data and for numerical facts they would give lot's of excel sheets . In excel sheet it is not easy to pin-point the region where sales are declining.

#### Solution - 
With Power BI , we can create a powerful dashboard , which will have all the major parameter it required and we can easily pin-point the region where sales are declining and it have many other useful features such send targeted mail , create custom mobile view dashboard and more.

#### Planning - 
Project Planning using AIM's grid and data discovery. 
AIMS Grid  - it is a project management tool and it has four components to it
1. Purpose - What we want to do exactly ?
             To unlock sales insights that are not visible before for the sales team for decision support and automate them to reduce manual time spent in data gathering.
2. Stake Holders - Who will be involved ? Here in this case Sales director , marketing team , IT , Data & analytics team
3. End Result - What we want to achieve ? An automated dashboard providing quick & latest sales insghts in order to support data driven decision making .
4. Success Criteria - How you defined you project was succcessfull ? Dashboard covering sales order insights with latest data available .  Sales analyst stop data gathering manually inorder to save 20% of their business time.

![image](https://user-images.githubusercontent.com/29626511/177531459-f09d373b-aaf2-4b40-9298-20e8e613260e.png)

### Why don't we extract data directly from MySQL ?
For extracting data directly from mysql database , it will slow down and affect the main stream business.

#### Data cleaning and ETL 
PowerQuery is a tool to transform our data .
Power BI have data model which shows relationship between different table.
Star Schema - here we have a fact table like transactions table and dimension table like entity table customer name .

#### Challenges Faced
![image](https://user-images.githubusercontent.com/29626511/177926694-4fdba4ee-0de1-44f8-b3c7-1d6dbe21ba7a.png)

As we can see the currency are of four types in the database , but it should be of only two type INR and USD.
Upon looking into database more carefully , I found that maximum of records were present with currency in INR\r and USD\r. So we only took the records whose currency were in INR\r and USD\r.




