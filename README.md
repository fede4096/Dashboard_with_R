# DASHBOARD WITH R 

A Dashboard is a tool used for information management and business intelligence. Much like the dashboard of a car, data dashboards organize, store, and display important information from multiple data sources into one, easy-to-access place. Behind the scenes, a dashboard connects to your files, attachments, services and API’s, but on the surface displays all this data in the form of tables, line charts, bar charts and gauges.

## Target

The aim of this repository is to show the potentiality of R statistical software in deploying a Dashboard about a real business problem.

## Data Source: https://www.kaggle.com/blastchar/telco-customer-churn
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets].

Customer churn, also known as customer attrition, occurs when customers stop doing business with a company or stop using a company’s services. By being aware of and monitoring churn rate, companies are equipped to determine their customer retention success rates and identify strategies for improvement. 
## Data Content
Each row represents a customer, each column contains customer’s attributes.

The data set includes information about:

1. Customers who left within the last month – the column is called **Churn**
2. Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
3. Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
4. Demographic info about customers – gender, age range, and if they have partners and dependents
## Before You Begin
Before you begin I recommend you read about the basic building blocks that assemble an R Dashboard:

- [R Markdown](https://rmarkdown.rstudio.com), an authoring framework for data science.
- [Shiny](https://shiny.rstudio.com), an open source R package that provides an elegant and powerful web framework for building web applications using R-
- [FlexDashboard](https://rmarkdown.rstudio.com/flexdashboard/), an R package which enables to create easy interactive Dashboard within R Markdown documents.

## Programming Languages
If you want to copy & paste the code and reproduce or change the Dashboard on your own, make sure you have installed all of the following prerequisites:

- [R](https://www.r-project.org)
- [R Studio](https://rstudio.com)

Instead, if you just want to visualize the Dashboard, you don't need to install them, because the application is hosted on [Shiny Apps](https://www.shinyapps.io), a platform providing R servers.

## Achievement
The Dashboard has 4 pages:

1. **Exploratory Data Analysis**: frequency distributions and cluster analysis.
2. **Results of Churn Analysis**: comparison between 6 classifiers in terms of their performance on test set.
3. **Dataset**, pre-processed and cleaned.
4. **Technical Notes**, for a better understanding of measures used within the analysis.











