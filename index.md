# Portfolio

## Academic Projects

### Climate Change Misinformation Detection

My complete implementation of year end project in [***COMP90042: Natural Language Processing***](https://handbook.unimelb.edu.au/2020/subjects/comp90042) by University of Melbourne (2020).

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/nghetrung/climate-change-fake-news)
[![Open Research Poster](https://img.shields.io/badge/PDF-Open_Research_Poster-blue?logo=adobe-acrobat-reader&logoColor=white)](pdf/NLP_project.pdf)

In this project, I applied different machine learning and data preprocessing approaches to detect misinformation about climate change. The project has 3 main phases:

1. Data Collection: After building different models and getting low quality results, I decided to crawl additional article about climate change from trusted websites. Then I performed multiple text proprocessing steps to prepare for model building phase.
2. Model Building: Apply different machine learning models
3. Model Evaluating: Evaluate and compare model performances

---
### NLP Assignments

My solutions for the assignments in [***COMP90042: Natural Language Processing***](https://handbook.unimelb.edu.au/2020/subjects/comp90042) by University of Melbourne (2020).

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/nghetrung/COMP90042)

The first one is about text preprocessing and classification on rumour data on Twitter. My task is to predict, given a tweet and its reactions, whether it is a rumour or not. I first need to create training, development and test partitions from the preprocessed events and convert the bag-of-words representation into feature vectors. After that, I implement two text classifiers: Naive Bayes and Logistic Regression, tune the hyper-parameters of these classifiers and print the task performance for different hyper-parameter settings.

For the second assignment, I will be quantifying the similarity between pairs of words of a dataset using different methods with the word co-occurrence in the Brown corpus and synset structure of WordNet. Firstly, I will preprocess the dataset to filter out the rare and ambiguous words. Secondly, I will calculate the similarity scores for pairs of words in the filtered dataset using Lin similarity, NPMI and LSA. Lastly, I will quantify how well these methods work by comparing to a human annotated gold-standard.

For the detailed solution codes, you can use the github links above.

---
### Potential Donators

My implementation and report of final year project in [***MAST90107: Data Science Project***](https://handbook.unimelb.edu.au/2020/subjects/mast90107) by University of Melbourne (2020).

[![Open Research Poster](https://img.shields.io/badge/PDF-Open_Research_Poster-blue?logo=adobe-acrobat-reader&logoColor=white)](pdf/Industry_Project__Final_Report_G14.pdf)

In this project, my team works with <a href="https://www.oaktreecapital.com/about">Oaktree</a> - an American global asset management firm specializing in alternative investment strategies. Our task was to deliver two requirements of our client:

1. Develop tools (e.g. scripts, dashboards, applications) to better manage/monitor/analyse our data.
2. Identify strategies to increase donations to Oaktree. For example, this could involve identifying the characteristics of people who raise most of the money for Live Below the Line.

For the first requirement, we create an R Shiny app which serves as a data cleaning tool to help our client saves time performing tedious data preparation tasks before any further analysis.

<center><img src="/images/cleaning_app.jpg" width="400" height="auto"></center>

To identify recommended strategies to increase donations for Oaktree, we segmented the donors into different groups based on the Recency, Frequency and Monetary features using unsupervised K-mean model. 

Finally, we try several machine learning models to predict whether a customer is of High, Medium or Low value based on the features they have. The best predictive result goes to XGBoost model.

<center><img src="/images/xgboost.jpg" width="400" height="auto"></center>

---
## Dashboards

While working in banking industry (BIDV), as a Data Analyst, I built interactive dashboards for different purposes using Tableau 

### Paygate (Bill Payment)

BIDV Paygate is an online payment gateway system for Fintech partners linking e-wallets. The system provides APIs for authentication and banking payment services for third parties, e-commerce platforms, and public services.
My task is to build a dashboard displaying the performance of the system in terms of transaction volume and value. Using Tableau, I had created a Monthly KPI dashboard with three main time-series views: Month-to-date, Previous Month, and Year-to-date transaction volumn or value depending on which one users want to see using filter. Each view also shows Month-over-Month (MoM) and Year-over-year (YoY) percentage change. User can filter to see data for different providers, service types, banking channels and time periods. Click on the image below to see my full dashboard.

<a href="https://public.tableau.com/views/ThanhtonhanPaygate/DetailDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link"><img src="https://img.shields.io/badge/tableau-%23E97627.svg?&style=for-the-badge&logo=tableau&logoColor=white" /></a>
<center><a href="https://public.tableau.com/views/ThanhtonhanPaygate/DetailDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link"><img src="images/Monthly KPI dashboard.png"/></a></center>

---
### Digital Customers

This dashboard includes animated running charts which show number of digital customers (customers who use digital service) through time. By looking at the dashboard, we can see the growth in number of customers in our digital services.

<a href="https://public.tableau.com/views/DigitalCustomers/DigitalCustomer?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link"><img src="https://img.shields.io/badge/tableau-%23E97627.svg?&style=for-the-badge&logo=tableau&logoColor=white" /></a>
<center><a href="https://public.tableau.com/views/DigitalCustomers/DigitalCustomer?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link"><img src="images/Digital Customer.png"/></a></center>

---
### RFM Analysis

As part of a Customer Analysis problem, I built a Customer Segmentation dashboard based on results of RFM analysis. The Tree Map segments customer into 6 groups based on Recency, Frequency and Monetary scores. It also serves as a filter across the whole dashboard. The Ternary chart represents each customer as an individual point with each corner represents RFM metric.

<a href="https://public.tableau.com/views/RFMCustomers/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link"><img src="https://img.shields.io/badge/tableau-%23E97627.svg?&style=for-the-badge&logo=tableau&logoColor=white" /></a>
<center><a href="https://public.tableau.com/views/RFMCustomers/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link"><img src="images/RFM Dashboard.png"/></a></center>

---
## Recommendation System

I joined a video recommendation project while I was working at Viettel Cyberspace Center (now known as Viettel AI). 

Initially, my task was to analyze user watching behaviours. The data include Video's metadata and User's watching logs data. From these 2 data, I performed feature engineering to create new features for further analysis such as: Video Duration Type, Watch Percentage, Average Watching Duration, Number of Videos Watched, Number of Categories Watched, etc.

From there, I applied Clustering techniques to analyze users watching behaviour and segment them into different groups based on the categories they watched, duration of the videos they watched, time of the day when they watched and time of the week they watched. Using my results, other member integrate it to the existing recommendation model for improvement.

### Data Engineering

While analysing the users behaviour data, I acknowledged the importance of having a central database for my data science team. The data was provided through kafka stream and saved into text file periodically. It was inconvenient when other members asked for new data or later when I was working on creating a system to monitor the metrics and performance of the model. Therefore, I decided to create a database for Myclip's data using PostgreSQL in a Docker container. I used Apache Airflow to schedule data ingestion jobs. The result is a structured, easy to use database that other memeber can quickly query to get their desired sample. 

### Metrics Monitoring

The recommendation system was running in production for sometimes but the metrics hadn't been captured and tracked. It is crucial to monitor the metrics to verify the model performance. I wrote a script to collect clickstream data on our website, store it in database and then build a dashboard to monitor the Click-through rate metrics. With the monitoring system running, my team and our customer was constantly notified about the performance of the model and thus improving it when needed. 

---
## MLOps

After working in two different organizations, my view about Machine Learning has changed significantly. When I was in University, all I need to focus on is learning different algorithms, model architectures, and trying to get the best accuracy or ROC score as possible. But now in real business scenarios, there are a lot more problems. Most of them, as you may already know, is the quality and availability of data. But that happens everywhere even in top tier organizations. The real pain points are the culture and procedure while working in Machine Learning projects. Since the AI trend emerged, everyone is trying to be a data driven company. They tried to solve everything with AI without considering cost and benefit, just because it sounds nice. Sometime, the reason to start a Machine Learning project does not come from the business team, therefore the objective is often not very clear. The business goal can be well achieved by performing simple data analysis and visualization, without Machine Learning.

When Machine Learning is the right thing to do, most organizations still do it in an immature way. There are no experiments tracking during model development as well as metrics/objectives monitoring in model evaluation. At Viettel AI, I had a chance to work with a Kubernetes cluster. I had built MLFlow platform to serve as an experiment tracking platform where other data scientists can record their model experimentations. I had also built a model deployment component using Seldon Core. The framework helps data scientist package and deploy their models as API endpoints to Kubernetes cluster. Model's endpoints can then be monitored by Prometheus and visualise on Grafana Dashboard.

Later on I researched on how to build and use Kedro pipeline for experimenting machine learning models. The tool is really helpful for data scientist and machine learning engineer as an end-to-end data science pipeline. 

### Kubernetes Deployment

Later, I had been given a task to migrate and deploy the recommendation system to the Kubernetes clusters. The Recommendation API server was initially running on-premise server using Docker along with several batch jobs in Airflow. Data received from Kafka and stored in file format. My task was to design the pipeline and deploy the Recommendation API server to run on Kubernetes. The system consists of several components. Kafka for data ingestion. Redis, Postgresql, Milvus for data storage. Airflow for running batch jobs. The API server which loads the data from storages, running model and return the recommendation results. Prometheus and Grafana for performance monitoring. Combining with ArgoCD, I had successfully made a Recommendation System API server to automatically redeploy on Kubernetes whenever the source code had been updated and pushed to Git.

### Lead Allocation Service

At Techcombank, I took on a key role in developing and maintaining a Lead Allocation service powered by Constrained Optimization. This service automates the lead assignment process, replacing manual distribution with a smart, rules-based engine that matches leads to the right sales agents based on multiple constraints. The result: a drastic reduction in assignment time and a more efficient, scalable workflow. This project sharpened my skills in algorithmic problem-solving and gave me hands-on experience building real-time decision-making systems in a high-stakes environment.

### Cloud Platform

At Techcombank, I also applied my MLOps skills to quickly ramp up on the Databricks platform. I set up automated workflows to handle data preparation and scheduled prediction tasks, eliminating the need for manual intervention and streamlining the entire pipeline. By integrating MLflow, I was able to track model experiments more effectively, monitor performance across versions, and maintain better control over the model lifecycle. This experience deepened my understanding of production-grade ML systems and reinforced the importance of automation and traceability in delivering reliable, scalable machine learning solutions.

---
<center>© 2024 Trung Nguyen. Powered by Jekyll and the Minimal Theme.</center>
