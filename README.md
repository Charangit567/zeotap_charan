# zeotap_charan
Data Science Assignment: eCommerce 
Project Overview
This project involves analyzing an eCommerce dataset to derive business insights, build predictive models, and segment customers based on their transactional and profile data. The dataset consists of three key files: Customers, Products, and Transactions. The main objectives of the project are:

Perform Exploratory Data Analysis (EDA) to uncover key trends and insights.
Build a Lookalike Model to recommend similar customers based on profile and transaction history.
Perform Customer Segmentation / Clustering to group customers into meaningful segments for targeted marketing.
Dataset Files
This repository contains the following files:

Customers.csv:
Contains data on each customer, including their unique identifier, region, and signup date.
Products.csv:
Contains details of products, including their name, category, and price.
Transactions.csv:
Contains transactional data, including customer ID, product ID, transaction date, quantity, and total value of each purchase.
Project Tasks
Task 1: Exploratory Data Analysis (EDA)
Objective: Clean and analyze the data using various statistical and visualization techniques. Derive business insights to identify customer behaviors, product trends, and other valuable metrics.

Deliverables:

Jupyter Notebook with EDA code and visualizations.
PDF report with at least 5 business insights derived from the data.
Task 2: Lookalike Model
Objective: Build a recommendation system that finds the top 3 most similar customers for a given customer based on profile and transaction history. Use customer and product information to calculate similarity scores.

Deliverables:

Lookalike.csv: CSV file with the top 3 lookalikes and their similarity scores for the first 20 customers.
Jupyter Notebook explaining the model, including code and methodology.
Task 3: Customer Segmentation / Clustering
Objective: Perform customer segmentation using clustering algorithms to group customers based on transactional and profile data. Use relevant clustering metrics (e.g., DB Index) to evaluate cluster quality.

Deliverables:

PDF report on clustering results, including:
The number of clusters.
Clustering evaluation metrics (DB Index, Silhouette Score, Inertia, etc.).
Jupyter Notebook with clustering code and visualizations.
How to Use
Clone or download this repository to your local machine.
Ensure you have the necessary Python libraries installed:
pandas
numpy
scikit-learn
matplotlib
seaborn
Open the Jupyter Notebooks to view the code, run the analysis, and generate the required reports.
Follow the file naming convention to ensure consistency with your submissions:
FirstName_LastName_EDA.pdf
FirstName_LastName_EDA.ipynb
FirstName_LastName_Lookalike.csv
FirstName_LastName_Lookalike.ipynb
FirstName_LastName_Clustering.pdf
FirstName_LastName_Clustering.ipynb
