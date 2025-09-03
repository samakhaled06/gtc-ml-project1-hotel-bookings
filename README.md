# gtc-ml-project1-hotel-bookings
Overview:
This project focuses on preparing hotel booking data for machine learning.
Our goal is to clean, preprocess, and engineer features from hotel_bookings.csv so that it can be used to build a model predicting booking cancellations.

Steps Done:
Exploratory Data Analysis (EDA)
Done summary statistics.
Visualized missing values.
Detected outliers.

Data Cleaning:
Imputed missing values (company, agent, country, children).
Removed duplicate rows.
Handled outliers (capped ADR > 1000).
Fixed data types (dates, numeric columns).
Created new features:
total_guests
total_nights
is_family

Encoded categorical variables (one-hot + frequency encoding).
Removed data leakage columns (reservation_status, reservation_status_date).
Final Dataset:
Split into training (80%) and testing (20%) sets.

Tools & Libraries:
Python (Pandas, NumPy, Scikit-learn).
Visualization (Matplotlib, Seaborn, Missingno).

Business Goal:
Reduce last-minute booking cancellations.
Preparing clean and reliable data, future machine learning models can predict cancellations.
