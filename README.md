🧠 Google Play Store Data Analysis & Feature Engineering
📌 Project Overview

The Google Play Store hosts millions of apps serving billions of users.
In this project, we analyze over 10,000 apps to uncover insights about:

Most popular app categories 📱

Apps with the highest installs and ratings 🌟

Pricing trends 💰

And the overall app market structure.

🎯 Objective

To perform Exploratory Data Analysis (EDA) and Feature Engineering on the Google Play Store dataset to:

Identify the most popular categories

Find the app with maximum installs

Discover which features influence app success

🧩 Steps Involved
1️⃣ Data Cleaning

Removed missing and inconsistent values

Converted columns like Reviews, Size, Price, Installs to proper numeric types

Handled special cases such as 'Varies with device' in Size

Parsed and extracted Day, Month, Year from Last Updated date

2️⃣ Exploratory Data Analysis (EDA)

Univariate and Bivariate visualizations using Matplotlib and Seaborn

Identified top 10 app categories

Found most installed and most rated apps

Detected data skewness in features like Reviews, Size, Installs, Price

3️⃣ Feature Engineering

Converted categorical data to numerical format

Derived new time-based features (like update year, month, day)

Cleaned text-based columns and removed duplicates

Saved the cleaned dataset for further ML model building

📊 Key Insights

Family and Games are the most popular categories (≈ 29% of all apps).

Subway Surfers is the most installed game.

Google Drive tops productivity apps.

Instagram leads the social category.

Around 271 apps have a perfect 5-star rating ⭐.

The GAME category dominates with over 35 Billion installs.

 Tech Stack
Category	Tools/Libraries
Programming	Python 
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Feature Engineering	Scikit-learn
Dataset	Google Play Store (10,841 rows × 20 columns)
 Results

✅ Cleaned dataset ready for model building (data/google_cleaned.csv)
✅ Actionable insights about app performance and user preferences
✅ Demonstrates strong EDA, preprocessing, and visualization skills

 Ideal For

📊 Data Analyst | 🧠 Data Scientist | ⚙️ ML Engineer
Perfect to showcase real-world data wrangling & storytelling skills to recruiters.

