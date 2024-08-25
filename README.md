# UK Train Rides
## This report is about the analysis of train rides in the UK train. The objective of this analysis is to provide a clear understanding of the most travelled route, peak travelled time, variables in ticket types by revenue, on-time performance, and other contributing factors.

## Executive Summary
The dataset that was used in this project was from [Maven Analytics April 2024](https://mavenanalytics.io/data-playground). It provides an interactive Power BI dashboard aimed at providing an insight of the overview of over **31,000 train rides** across 65 routes in the United Kingdom, which generated a **total revenue of £742,000**. Additionally, the dashboard put forward visualizations of performances of the train across different suburbs and cities.

[Click here to view and interact with the dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjU5ODIxMmMtZTVmNy00Y2YyLWFjM2ItODg5YzY1MGM3MTZhIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

## Project Background
Train system is the mainstream means of transportation in the United Kingdom, many people use the train for their daily commuting between their homes and workplaces, especially in urban areas like London, Manchester, and Birmingham as seen in the top 10 popular routes in the analysis. This analysis is targeted in providing some significant recommendations that will help in more dissemination and improvement of the UK rail system to meet modern transportation needs across the country.

## Overview of the Data
The data provided some useful information that were utilized in the course of this analysis such as transaction ID, departure station, arrival destination, journey status, ticket class, reason for delay and so on.

## Data Extraction and Transformation
The data was cleaned and transformed using Power Query Editor in Power BI. Key transformations include:
- Blank Rows Removal: Blank rows were removed to maintain data integrity.
- Merging of columns: Columns were merged to improve data consistency and to consolidate information on routes. The Route column was formed by merging the columns for Departure Station and Arrival Station respectively.
- Column Renaming: Some columns were renamed for better readability.
- DAX Function: The SWITCH DAX function was used in grouping the departure time into 3 hours batches to declutter a visual line chart in Power BI.

## Tools and Technologies Used
- Power BI: The fundamental tool used in this project was Power BI, which helped in the creation of visualizations and dashboards to extract and display insights from the data.
- Power Query Editor: An advanced feature of Power BI, Power Query Editor was employed for data transformation and cleaning. This tool was used to perform various operations such as removing duplicates, eliminating blank rows, formatting columns, and replacing values across different columns
- Microsoft Excel: Microsoft Excel played a crucial role at the beginning of the project. It helped in the understanding of the data structure as well as some light data cleaning. It also served as a guide for subsequent data transformations using the Power Query Editor.

## Description of the columns and data dictionary:
The Data Dictionary provides a centralized repository of definitions and descriptions of vital information in the dataset, ensuring consistency in terminology and usage across the datasheet.
- Transaction ID: Unique identifier for every purchase ticket.
- Date of purchase: The date each ticket was purchased.
- Types of Purchase: This column categorized the two means of purchasing a ticket.
- Payment method: This highlighted the mode of payment.
- Railcard: This column grouped the total travelling population into adults, seniors, disabled and None.
- Ticket class: This column differentiates the travelling classes.
- Price: Generated revenue.
- Departure station: These are stations where the train takes off.
- Arrival station: The arrival station, the last terminals.
- Departure time: Time at which trains depart to various destinations.
- Arrival time: Time of arrivals for each train.

## Project workflow
- Data Exploration and Preparation: Begin with an initial exploration and basic cleaning of the data in Microsoft Excel to grasp its structure.
- Data Transformation and Refinement: Perform additional data cleaning and transformation using Power Query Editor in Power BI to ready the dataset for in-depth analysis.
- Dashboard Creation: Develop an interactive dashboard in Power BI, integrating different visualizations to display sales performance metrics.
- Analysis and Interpretation: Examine the visualized data to uncover insights related to time trends, top 10 most popular route, method of payment, Railcard category, Revenue and on time performance of the train.
- Deployment: Uploading the dashboard to the Power BI service, enabling access through an interactive web link

## Project objective: The objective of this analysis is focusing on UK train rides, the goal is to create a comprehensive dashboard and set of reports that provide actionable insights into travel patterns, revenue, and performance metrics. The project is targeted at:
- To Identify the most frequently travelled routes and visualize route popularity.
- To Determine peak travel times to understand demand fluctuations and optimize scheduling.
- Assess the revenue contribution of different ticket types and classes (first class, standard).
- Evaluate punctuality and identify factors contributing to delays.

## Data Analysis & Visualization:
Following the completion of data cleaning and preparation, I moved on to analysis and visualization. This was done to facilitate easy navigation and provide a clear understanding of the project.
Some Key Insights from the data visualization are summarized below:
- Overview: From the dashboard, it’s observed that the number of total completed transactions is 31,653 emerging from 65 routes across different cities in the United Kingdom. These transactions generated a total revenue of £742,000. This includes all ticket classes; the information deduced from the data as shown on the dashboard entails that over 70% of the above revenue were from the sales made on standard ticket class with £592,522 while first class tickets generated a lesser percentage of the total revenue with £149,399.
- Method of payments: The three categories of payment method were all identified with different percentage values contributed. Credit cards were the majorly used mode of payment by the United Kingdom train travellers. The number of recorded transactions by credit card is 19136; this figure made up about 60.46% of the total transaction by payment method, followed by contactless method of payment with a completed transaction of 10,834 which fairly contributed 34.23% of total payment method, while the debit card is the least contributed of total payment method with 5.32% with a transaction number of 1,683.
- Categories of Railcards: Railcards are typically available to specific groups of people such seniors, adults, and people with disabilities. The data dictionary states that these people get a one-third off their ticket price. From the analysed data, “none”, which represents people with no railcards stands out with the highest figure of 20,918. Adults with railcards are 4,846 while seniors and disabled recorded 3,089 and 2,800 users respectively.
 
## Recommendations
- Targeted Marketing for First-Class Sales: With only 20% of total revenue coming from first-class tickets, strategic promotions or loyalty programs could be introduced to boost first-class ticket sales.
- Increased Awareness of Railcards: The dominance of the "none" category suggests a need for better promotion and awareness of railcard benefits, particularly for adult and senior railcard options, to encourage more users to take advantage of discounts.
- Enhanced Payment Flexibility: With credit cards being the preferred payment method, increasing support for other payment methods such as mobile wallets or flexible payment plans could attract a wider customer base.
- Improved Customer Engagement: Personalized communication and incentives could be directed at users of contactless payments and debit cards to increase transaction volume and loyalty among these groups.
These recommendations, if implemented, could help optimize revenue and customer satisfaction while addressing underutilized areas of the current service offering.

## Conclusion
The data analysis highlights key trends in train ticket transactions across the United Kingdom, providing insights into revenue distribution, payment preferences, and railcard usage. A total of 31,653 transactions generated £742,000 in revenue, with over 70% of this coming from standard-class ticket sales (£592,522). Payment methods indicate that credit cards are the most popular, accounting for 60.46% of transactions, followed by contactless payments at 34.23%, and debit cards at 5.32%. In terms of railcard usage, the majority of transactions involved no railcard (20,918), suggesting low uptake among specific categories like adult, senior, and disabled railcards, which together accounted for less than half of the transactions. The findings from this analysis also highlights the dominance of standard-class tickets and credit card payments, along with a significant opportunity to enhance railcard adoption among target groups.
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

