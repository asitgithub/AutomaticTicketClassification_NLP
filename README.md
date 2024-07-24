# Automatic-Ticket-Classification-NLP
This NLP model, developed by Asit Kumar Singh, automatically categorizes customer complaints based on the product or service using advanced syntactical processing capabilities.

## Problem Statement

Customer complaints are crucial for financial companies as they often highlight deficiencies in their products and services. Efficiently resolving these complaints minimizes customer dissatisfaction and bolsters loyalty, while also providing insights on how to enhance services to attract more customers.

Handling these unstructured text complaints traditionally requires significant manpower to evaluate and assign each ticket to the appropriate department, becoming increasingly cumbersome as the company expands.

In this project, Asit Kumar Singh, working as an NLP engineer, aims to automate the customer support ticket system for a financial institution offering diverse services like credit cards, banking, and mortgages/loans.

## Business Goal

The objective is to construct a model capable of classifying customer complaints by their related products/services, thus streamlining the ticket segregation process for rapid issue resolution.

Utilizing non-negative matrix factorization (NMF) for topic modeling, the model identifies patterns and recurring words in each ticket. This analysis reveals critical features for each category cluster, aiding in the identification of predominant complaint topics.

Topic modeling will be conducted on unlabeled .json data from the company, using NMF to categorize tickets into five clusters based on products/services:

- Credit card / Prepaid card
- Bank account services
- Theft/Dispute reporting
- Mortgages/loans
- Others

This structured approach allows for mapping each ticket to its respective department/category, forming a dataset to train supervised models like logistic regression, decision trees, or random forests. These models are then employed to classify new customer complaints accurately.

## Solution Approach

1. Data loading
2. Text preprocessing
3. Exploratory data analysis (EDA)
4. Feature extraction
5. Topic modeling
6. Model building using supervised learning
7. Model training and evaluation
8. Model inference

This solution, crafted by Asit Kumar Singh, aims to enhance the efficiency of handling customer complaints, providing a scalable and effective approach to customer service management within financial organizations.