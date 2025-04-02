#✅ Project Overview

A machine learning project aimed at evaluating street safety based on reported crimes, service requests, and traffic accidents.

Focused on the City of Chicago, with data sourced from the official open data portal.

Targeted to assist urban planners, law enforcement, and communities in making safer neighborhoods.

🗂 Data Summary
Combined three large datasets related to crime, city service calls (311), and vehicle crashes.

Geolocation data (latitude/longitude) used to link and analyze safety trends across specific locations.

Cleaned, filtered, and transformed data for modeling.

🔧 Data Engineering
Cleaned and standardized datasets to handle missing values and remove noise.

Merged datasets using geospatial coordinates to create unified location-level insights.

Created new features (e.g., total incidents per location) to represent risk levels.

🧠 Machine Learning Models
Used multiple classification algorithms to predict if a location is safe or unsafe:

Logistic Regression

Random Forest

XGBoost

Evaluated performance using accuracy, confusion matrix, and model comparison.

📊 Insights & Findings
Locations with frequent traffic crashes and crimes were most likely classified as unsafe.

Most areas were predicted as safe, but several clusters were flagged as higher risk zones.

Spatial visualizations helped clearly identify and communicate these clusters.

🗺 Visualizations
Developed interactive maps to display safe vs unsafe zones using Python's mapping libraries.

Provided an easy-to-understand visual tool for stakeholders to act on.

📌 Recommendations
Focus public safety efforts and urban development on high-risk locations.

Encourage proactive community engagement and resource allocation.

Use predictive insights to support long-term planning for safer cities.

🧰 Tech Stack
Python (Pandas, GeoPandas, Scikit-learn, Folium)

Jupyter Notebooks

Data visualization and geospatial analysis tools
