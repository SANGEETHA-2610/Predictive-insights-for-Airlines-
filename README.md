# Predictive-insights-for-Airlines-
This project generates a synthetic flight dataset and performs exploratory data analysis (EDA) to understand flight delay patterns.
It was developed as part of my Machine Learning Internship, focusing on data generation, preprocessing, and visualization — the foundational steps before model training.

💡 About This Project

During my Machine Learning Internship, I created this project to simulate realistic flight data for use in data analytics and model experimentation.
Since real flight datasets can be large or restricted, this project produces a custom, reproducible dataset with meaningful features that mimic real-world airline operations.
The dataset and visualizations serve as a base for:

Training machine learning models to predict delays
Practicing data preprocessing and feature extraction
Performing EDA and correlation analysis

🧠 Project Overview

The goal of this project is to:

Generate realistic synthetic flight records using Python.
Perform visual analysis of delay patterns.
Prepare structured data for machine learning experiments.
This is a simple yet effective example of data simulation, transformation, and visualization workflow used in real ML projects.

🧩 Features

✅ Generates 10,000 random flight records with multiple attributes.
✅ Derives new features like:
DepHour (departure hour extracted from HHMM format)
Delayed (binary label if arrival delay > 15 minutes)
✅ Saves dataset as random_flight_data.csv.
✅ Creates visualizations:
Arrival Delay Distribution (Histogram)
Correlation Matrix (Heatmap)

🛠️ Technologies/Libraries Used

Pandas-Data manipulation and analysis
NumPy-Random data generation
Seaborn-Statistical visualization
Matplotlib-Plot customization and display
Random-Reproducible randomization

