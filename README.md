K-Means Clustering
Project Overview
This project focuses on analyzing mobile usage behavior and segmenting users into different groups using Machine Learning K-Means Clustering. The system groups users based on screen time, app usage, gaming activity, social media usage, and productivity app usage.

The project also includes:

Data preprocessing

Outlier removal

Feature scaling

Clustering

Data visualization

Problem Statement
Mobile users generate large amounts of behavioral data through app usage, gaming, screen time, and social media activity. Analyzing this data manually is difficult due to varying usage patterns.

This project aims to automatically segment users into meaningful groups using K-Means clustering to better understand mobile usage behavior.

Objectives
Analyze mobile usage behavior

Remove outliers for better clustering accuracy

Segment users into clusters

Visualize user groups using plots

Identify different categories of users

Technologies Used
Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Dataset Features
The dataset contains:

Daily Screen Time

Total App Usage Hours

Number of Apps Used

Social Media Usage Hours

Gaming App Usage Hours

Productivity App Usage Hours

Machine Learning Technique
K-Means Clustering
K-Means clustering is used to group similar mobile users into clusters based on their usage behavior.

Number of clusters used:

Python


Run
n_clusters = 4
Steps Performed
Import Libraries

Load Dataset

Data Cleaning

Outlier Removal using IQR Method

Feature Selection

Data Scaling using StandardScaler

Apply K-Means Clustering

Visualize Clusters

Analyze Cluster Results

Data Visualization
The project includes:

Scatter Plot

Pair Plot

Count Plot

Heatmap

3D Cluster Visualization

Use Cases
Personalized Recommendations

Targeted Marketing

User Behavior Analysis

Telecom Analytics

Customer Segmentation

Results
The model successfully grouped mobile users into different behavioral clusters such as:

Heavy Users

Social Media Users

Gamers

Productivity Users

Future Improvements
Implement DBSCAN clustering

Add real-time analytics

Deploy using Streamlit

Improve cluster accuracy

Author
Pranathi
