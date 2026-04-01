🍄 Exploring Mushrooms
Overview

This project explores a mushroom dataset to understand how different characteristics relate to whether a mushroom is edible or poisonous.

The goal was to practice working with real-world data — from cleaning and exploration to identifying patterns that could later be used for machine learning classification.

Objectives
Explore and understand the structure of the dataset
Analyse relationships between features and the target variable
Identify key factors that influence mushroom classification
Prepare the data for future machine learning use
Dataset

The dataset contains various categorical features describing mushrooms, including:

Cap shape, surface, and colour
Odor
Gill size and colour
Habitat

Each sample is labelled as:

Edible
Poisonous
Tools & Technologies
Python
pandas
numpy
matplotlib / seaborn
Jupyter Notebook
Approach
1. Data Exploration
Loaded and inspected the dataset
Checked for missing values and inconsistencies
2. Data Cleaning
Worked with categorical variables
Prepared the dataset for analysis
3. Visualisation
Analysed feature distributions
Compared features against the target variable
Identified patterns using plots
Key Insights
Some features (especially odor) are strong indicators of whether a mushroom is edible or poisonous
The dataset is entirely categorical, meaning encoding will be required for machine learning models
Certain features clearly separate the two classes, making this dataset well-suited for classification tasks
What I Learned
How to approach a new dataset from scratch
Working with categorical data in Python
Using visualisation to uncover patterns
Structuring a data analysis workflow
Next Steps
Apply classification models (e.g. Decision Tree, Random Forest)
Evaluate model performance using accuracy and other metrics
Perform feature importance analysis
Build a simple prediction tool
Project Structure
exploring-mushrooms/
│── data/  
│── notebook.ipynb  
│── README.md  
How to Run
git clone https://github.com/Madhurima077/exploring-mushrooms.git
cd exploring-mushrooms
jupyter notebook

Author

Madhurima Majumdar
