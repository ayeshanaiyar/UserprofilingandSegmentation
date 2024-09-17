# UserprofilingandSegmentation
# overview
This project provides a code for exploratory data analysis (EDA) and user segmentation of a dataset containing user profiles for targeted advertising purposes with the use of jupyter notebook.
# Prerequisites
1. Python 3
2. pip
3. Jupyter notebook
# Libraries
1. pandas
2. matplotlib
3. seaborn
4. nb format
5. sklearn
6. plotly.graph_objects
# Expolatory Data Analysis
Visualizations using seaborn showcase distributions of demographic variables (age, gender, device usage, education level, income), online behavior (time spent online, likes, click-through rates, conversion rates, ad interaction time), and top user interests.
A radar chart using plotly visually represents the average profiles of each user segment across key metrics, providing a clear comparison between segments.
# setup instructions
1. Create a virtual environment
2. Upload the dataset which provides an overview of the columns and identifies key user demographics, online behavior, and ad interaction metrics.
3. Installing required libraries
4. Run the cells sequentially to execute the code.
# User segmentation
The code performs K-means clustering to segment users into distinct groups based on relevant features:
1. Age
2. Gender
3. Income Level
4. Time Spent Online (Weekdays and Weekends)
5. Likes and Reactions
6. Click-Through Rates (CTR)
Five user clusters are identified, and their characteristics are analyzed.
# Processing technique
1. Load the data and check it null and stataistical values of data.
2. check the expolatory data analysis.
3. Apply clustering to segment the data.
# Results
It develops targeted ad campaigns that resonate with specific user segments.
Optimizes ad content and placement based on user demographics, interests, and online behavior.
Improve ad targets strategies for better reach and conversion rates.
