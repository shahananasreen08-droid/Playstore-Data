# 📱 Google Play Store Apps Analysis

## 📖 Description

This project focuses on analyzing the **Google Play Store Apps dataset** obtained from Kaggle. The dataset contains information about more than 10,000 Android applications, including their ratings, reviews, installs, price, category, and other attributes.

The goal of this project is to perform data analysis and extract meaningful insights about app performance, user preferences, and trends in the Android app market. This helps in understanding what makes an app successful.

---

## 🎯 Objectives

* To analyze the distribution of apps across different categories
* To study the relationship between ratings, reviews, and installs
* To identify factors affecting app popularity
* To explore pricing trends between free and paid apps
* To visualize insights using charts and graphs

---

## 📊 Dataset Information

* Dataset Name: Google Play Store Apps
* Source: [Kaggle](https://www.kaggle.com/datasets/whenamancodes/play-store-apps?utm_source=chatgpt.com "Play Store Apps")
* Total Apps: ~10,000+
* Format: CSV files

### Key Features (Columns)

* App – Name of the application
* Category – App category (e.g., Game, Business)
* Rating – User rating (1–5)
* Reviews – Number of user reviews
* Size – Size of the app
* Installs – Number of downloads
* Type – Free or Paid
* Price – Cost of the app
* Content Rating – Target audience
* Genres – App genres
* Last Updated – Last update date
* Android Version – Minimum Android version required

These attributes provide a complete overview of app performance and user engagement. ([Kaggle][1])

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas (Data Analysis)
* NumPy (Numerical Operations)
* Matplotlib & Seaborn (Data Visualization)
* Jupyter Notebook

---

## 🛠️ Features

* Data Cleaning and Preprocessing
* Handling missing values and duplicates
* Exploratory Data Analysis (EDA)
* Data Visualization (graphs, charts)
* Insights on app trends and performance

---

## 🚀 How It Works

1. Load the dataset using Pandas
2. Clean the data (remove null values, fix formats)
3. Perform exploratory data analysis (EDA)
4. Visualize important patterns using graphs
5. Interpret results and draw conclusions

---

## 💻 Installation / Usage

1. Download the dataset from Kaggle
2. Install required libraries:

   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the project in Jupyter Notebook
4. Run the cells step-by-step to see the analysis

---

## 📈 Key Insights

* Most apps on the Play Store are free
* Apps with higher reviews tend to have more installs
* Certain categories like Games and Tools dominate the market
* Ratings do not always directly correlate with installs
* Paid apps are fewer but often have higher quality ratings

---

## 📁 Project Structure

* `googleplaystore.csv` – Main dataset
* `googleplaystore_user_reviews.csv` – User reviews dataset
* `analysis.ipynb` – Data analysis notebook
* `README.md` – Project documentation


---

## 📌 Conclusion

This project successfully analyzes the Google Play Store dataset and provides useful insights into app trends, user behavior, and market dynamics. The findings can help developers and businesses make better decisions while creating and marketing apps.

Future improvements can include machine learning models to predict app success and recommendation systems.

---
