## Housing Price Prediction Using Set Theory and Venn Diagrams

# Project Overview
This project involves predicting housing prices based on a given dataset using three features to filter the pricing, such as, square footage, how many rooms, and parking availability. This project utilizes set theory and venn diagrams to categorize these features.
• Set A: Houses that have MORE than 2000 square feet.
• Set B: Houses with more than 2 rooms.
• Set C: Houses with parking availability.
The goal is to calculate the housing price based for each sector on the Venn Diagram that corresponds to the different combination of these features.

# Features
• Dataset: The datasets include information on houses, such as square footage, number of rooms, and parking availability.
• Set Theory: Used to divide houses into groups based on what features are provided. (e.g., Set A, Set B, Set C).
• Venn Diagram: A Venn Diagram is provided to visually represent intersections between each set, and the average housing price for each sector.

# How the Project works
1. Data Processing: The dataset is cleaned and categorized based on the defined sets (Sets A, B, C).
2. Set Analysis: The intersections between the sets are used to calculate average housing prices for each combination of conditions (e.g., A only, A n B, A n B n C).
3. Prediction Model: Based on the set of intersections, avergae prices are predicted for houses that fall into each sector of the Venn Diagram.

# Files in the Repository
• main.py: Contains the code for data processing, set operations, and calculating average prices in each sector.
• dataset.csv: The dataset used for the prediction model.

# How to run the Project
You can run the project by clicking on the "Housing_Crisis_Project.ipynb" file and clicking "Open in Colab" which will redirect you to Google Colab.

# Results
The average housing prices for different sectors of the Venn Diagram are computed and displayed in tabular form which allows for comparison of housing prices based on the three features, square footage, rooms, and parking availability.
