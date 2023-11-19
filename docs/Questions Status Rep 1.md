
Briefly characterize the status of your project*

As of now, our team has selected a project topic, created and started to collaborate on a GitHub repository and using visual code editor, and conducted a thorough assessment of the associated dataset. Two crucial phases have been completed:
1.	Business Understanding: During this phase, we delved into a discussion about the project’s goals, understanding potential use cases and recognizing any challenges that might arise. This has provided us with a direction of where the project might head and the value it aims to deliver to our client.
2.	Data Exploration: An initial dive into the dataset allowed us to grasp its structure, pinpoint key attributes, and gather preliminary insights. In doing so, we identified certain data quality concerns and gathered an understanding of data distributions, including the characteristics of overall clients, and those who have churned and not.  
These two phases allowed us to uncover initial patterns which could prove essential for our subsequent analytic endeavours. Currently, we are tuning our project scope, balancing leveraging our dataset to its full potential with the value it might generate to our client.


What have been your main challenges in the project, so far?*

Business objectives complexity: Besides having access to our client’s dataset, lacking context about business objectives and overall client strategy requires us to do a more in-depth assessment to identify its main needs. Without having access to our client for initial assessment meetings, it is being hard to figure out expectations and priorities, which poses a challenge in aligning everyone to a singular vision and define clear non-vague goals.
Defining the project scope: With access to 50 features (19 quantitative variables and 31 qualitative) and data about 7043 clients, it becomes a challenge to determine which attributes are truly relevant and which can be excluded or combined. We understand there is abundance of starting points for our analysis and a multitude of potential use cases which present a challenge in narrowing down our focus. Too many analyses could offer value but can also dilute the impact and lead to inefficiencies. For example, our team thinks it would be valuable to build a predictive model to predict the probability of churning customers. However, we don’t have access to historical data of another time frame (quarter) to train our model. Thus, we most likely will pursue clustering analysis to find the characteristics of potential churn clients.
Resource allocation: We have the risk of consuming significant resources, including time and computational power on aspects that might not deliver proportional value, so we need to balance between depth and breadth of analysis.



What insights/learnings have you achieved so far in the project?*

In each phase we have had several insights so far:
1.	Business Understanding: 
•	As dataset inputs we have data about customer demographics, location (and population density), services and offers adherence and customer status. This offers a unique opportunity to do customer behaviour and preferences analysis as well as to identify customer paint points (with relation to churn rate). By doing this, we can provide our client strategic initiatives that drive customer retention, enhance revenue and improve customer satisfaction.
•	Our client understanding:
i.	Our client is a multifaceted telecommunications service provider. At its core, it offers a suite of communication solutions to its customers which include telephony services (home phone services with options to have multiple telephone lies and a breakdown of long-distance charges), internet services (DSL, Fiber Optic, and Cable and add-ons like online security service, online backup service, device protection plan, premium technical support), streaming, billing and payment with flexibility options raging from month-to-month to one or two-year contracts, supporting diverse payment methods. 
ii.	Our client places a strong emphasis on customer feedback and data-driven insights. Using tools like IBM SPSS Modeler, they predict the likelihood of a customer churning, aiming to proactively address concerns (Churn Score variable) and evaluates customer satisfaction and monitor the CLTV to identify and retain their most valuable customers. Additionally, when a customer decides to leave the company, a systematic feedback process captures the reason behind their departure, categorizing it broadly.  
•	Customer segmentation would provide interesting insights to our client, based on variables such as services the customers use, CLTV categories, tenure, and other details, as it would reply to key questions such as “Which segments are the most profitable? Which segments have higher churn rate?”
•	Customer churn analysis and prediction would be relevant for our client, to understand the reasons for churn (“Which areas should the company work on? Which customers churn more or less?) as well as to predict which customers are most likely to leave in the coming period (by identifying customer risk groups)
•	Revenue analysis to understand within our client offering, which are the most popular services and how they correlate with other variables such as customers satisfaction, as well as to understand the penetration of additional services (e.g., backup, security, etc.).
•	Geographical analysis to analyse market penetration across regions and if there are specific regions where churn is higher or where certain services are more popular, as it would reply to key questions such as “To where should our client expand?”

2.	Data Exploration: In this phase we have understanded the structure of the data and identified the first impressions of patterns, relations and errors through basic information and statistics, visual exploration and in-depth exploration of key variables and their relationships. Key insights so far include (non-exhaustive):
•	With a rich dataset encompassing demographics, location specifics, population metrics, services availed, and customer status, the company is well-poised to make informed decisions, through its data and with our help, which includes 7043 rows (Clients) and 50 features, including 19 quantitative variables and 31 qualitative. 
•	We don’t have missing values in our dataset
•	We have 1860 clients that have churned. This represents a churn rate of ~27%.
•	Our client has had a revenue of 21 371 131.69 monetary units during the analysed period. Our client is present in the United States, in the State of California and the period of analysis is Quarter Q3.
•	We have done further exploration and visual exploration by analysing skewness and kurtosis and identified several variables that are highly skewed and highly peaked (kurtosis) which could indicate the presence of outliers which we later identified following the IQR method and with visual exploration by looking at boxplots and points that felt outside the whiskers. 
•	We have performed spearman correlation between numerical variables and identified high correlations for location variables (which is expected) and between charges and revenue variables as well as others. 
•	In a more in-depth analysis of customers who have churned and those who didn't we have found that senior customers have 2x higher churn rates, customers with dependents have very low churn rates (~6%), out of the top 5 cities in terms of client number, San Diego stands out as having the higher churn rate (~65%), those who have internet services compared to those who don’t have much higher churn rates (32% vs 7%, respectively). Additionally, those who have shorter term contracts have higher churn rates. 



What do you expect will be the next steps in the project?*
Guided by the insights from the business understanding and data exploration phases, our forthcoming steps will encompass data preprocessing and feature engineering. 
Subsequently, we will perform a (i) cluster analysis with several scenarios to segment customers. Based on the insights from this first analysis, we will adjust our planning.  Simultaneously we will do other analysis such as revenue analysis, geographic analysis, among others. 
