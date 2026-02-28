# DS_Traffic-accident-data-analysis
Analyzing traffic accidents data in india to identify patterns related to road conditions, weather, and time of the day. Visualizing accident hotspots and contributing factors
Task-05:
Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and analyze contributing factors.
This project was completed as part of a Data Analytics / Data Science Internship to demonstrate practical skills in data cleaning, exploratory data analysis (EDA), and visualization using Python.

 ## 🎯 Project Objectives
Analyze accident trends based on time of day
Understand the impact of weather conditions on accidents
Examine how road surface conditions contribute to accidents
Compare day vs night accident occurrences
Visualize accident hotspots using geographical data
Derive meaningful insights to support road safety analysis

----
 ## 📂 Dataset Information
The dataset was downloaded from Kaggle and provided as a ZIP file containing multiple CSV files:
File Name
Description
Used
AccidentBig.csv
Core accident details including date, weather, road surface, light conditions, and location
✅ Yes
CasualtiesBig.csv
Information about injured and killed persons
❌ No
VehicleBig.csv
Vehicle-level accident details
❌ No

 ➡️ Only AccidentBig.csv was used, as it contains all required features for Task-05.

 ----
## 🛠️ Tools & Technologies Used
Python
Pandas – Data loading and preprocessing
NumPy – Numerical operations
Matplotlib & Seaborn – Data visualization
Folium – Interactive accident hotspot mapping
Google Colab / Jupyter Notebook – Development environment
---
## ⚙️ Methodology
1️⃣ Data Extraction & Loading
ZIP file extracted using Python’s zipfile module

2️⃣ Data Cleaning
Automatically detected the date column to handle dataset variations
Converted date strings to datetime format
Handled invalid or missing date values
Filled missing categorical values with "Unknown"

3️⃣ Feature Engineering
Extracted time-based features:
Hour → Time-of-day analysis
Day → Weekday patterns
Month

4️⃣ Exploratory Data Analysis (EDA)
Accident distribution by hour of day
Accident frequency by:
Weather conditions
Road surface conditions
Light conditions (day/night)
Day of the week

5️⃣ Accident Hotspot Visualization
Used latitude and longitude (if available)
Generated an interactive heatmap using Folium

6️⃣ Contributing Factor Analysis
Cross-analysis of Weather Conditions vs Road Surface Conditions
Identified combinations leading to higher accident rates

## 📊 Visualizations Included
Accidents by Time of Day
Accidents by Weather Conditions
Accidents by Road Surface Conditions
Day vs Night accident comparison
Accidents by Day of the Week
Geographical Heatmap of accident hotspots

## 🔍 Key Insights
Most accidents occur during evening rush hours

Poor weather conditions significantly increase accident risk
Wet and slippery road surfaces contribute to a higher number of accidents
Night-time accidents are more frequent due to reduced visibility
Certain locations show high accident concentration (hotspots)

## 📈 Outcome
This project successfully demonstrates:
Real-world data preprocessing
Exploratory data analysis
Insightful visual storytelling
Practical application of Python for data analytics
It fulfills all requirements of Internship Task-05.

## 🚀 How to Run the Project
Upload the ZIP dataset to Google Colab or local environment
Extract the ZIP file
Run the notebook traffic_accident_analysis.ipynb
View generated visualizations and hotspot maps

👤 Author
Bhavishya sri Matangi
Data Analytics Intern

## 📌 Note
This project is created strictly for educational and internship purposes.

## OUTPUT
<img width="1599" height="1200" alt="image" src="https://github.com/user-attachments/assets/5d7ea6df-1893-470d-8e94-7ae3b5181071" />
<img width="1599" height="1200" alt="image" src="https://github.com/user-attachments/assets/aff36bfc-81d5-4ee6-ad52-cb4d7a7c748f" />
<img width="1599" height="1200" alt="image" src="https://github.com/user-attachments/assets/ec4e5a75-5c41-4779-8c51-ebe106ab0f90" />
<img width="1599" height="1200" alt="image" src="https://github.com/user-attachments/assets/f808aab9-d779-40f4-9b58-fb0c24e99fff" />
<img width="1599" height="1200" alt="image" src="https://github.com/user-attachments/assets/5409942f-1a6e-4e4b-b9e9-bc2997d172ae" />
<img width="1599" height="1200" alt="image" src="https://github.com/user-attachments/assets/12134e15-d4a7-4f74-b664-33f4567d87c6" />





