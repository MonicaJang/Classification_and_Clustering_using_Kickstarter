This repository contains a data science project focused on predicting Kickstarter campaign outcomes and identifying strategic project clusters using 2025 datasets. The goal is to provide actionable insights for creators to optimize their projects at the time of launch.

**📌 Project Overview**

The analysis is divided into two main tasks:
- Classification: Developing a machine learning model to predict whether a project will be "successful" or "failed" based only on information available at the launch point.
- Clustering: Grouping projects based on content characteristics (textual and visual) to identify distinct segments and their performance patterns.

**📊 Dataset**

- Source: Kickstarter 2025 Dataset.
- Note on Data: Due to GitHub's file size limit (100MB), the raw data file kickstarter_combined.csv (approx. 1.5GB) is not included in this repository.

**🛠️ Technical Implementation**

1. Predictive Modeling
- Objective: Predict project success at the moment of launch.
- Key Features: Category, funding duration, goal amount, name/blurb length, and the presence of videos.
- Algorithms: Gradient Boosting (GBM), Random Forest, and Logistic Regression.

2. Strategic Clustering
- Objective: Segment projects to understand different promotional strategies.
- Approach: K-Means clustering based on "Textual Information" vs. "Visual Content."

**💡 Business Recommendations**

- For Creators: Don't just focus on the funding goal. The quality of your "Story" (blurb length and video integration) is a significant predictor of backer engagement.
- For Platforms: Kickstarter can use these models to flag "at-risk" projects early on and provide automated suggestions for improving project descriptions.
