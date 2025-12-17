# Mini-Project: Rule Based Product Recommendation System Using Python

## 📌 Project Overview
- This project is a rule-based product recommendation system built using Python and JSON.
- It recommends products based on user ratings and simple logical rules, without using any machine learning algorithms.

## 🎯 Objectives
- Load and process user data from a JSON file
- Clean and structure inconsistent data
- Generate meaningful insights from ratings
- Recommend products using rule-based logic

## 🛠 Technologies Used
- Python
- JSON
- Built-in Python libraries

## ⚙️ Features Implemented
### 1️⃣ Data Loading
- Reads user data from a JSON file using json.load()
### 2️⃣ Data Cleaning & Structuring
- Converts string ratings (e.g., "four") into numeric values
- Removes extra spaces and standardizes text
- Handles missing values (e.g., age)
- Removes duplicate users based on name
### 3️⃣ Data Insights
- Calculates average user rating
- Calculates percentage of users with poor ratings (< 3)
### 4️⃣ Rule-Based Recommendation System
- Users with rating ≥ 4 are recommended Apple
- Users with rating < 4 are recommended Samsung
- Recommendations are generated using conditional logic

## ✅ Key Learning Outcomes
- Python file handling
- JSON parsing
- Data cleaning and preprocessing
- Rule-based recommendation logic
- Problem-solving and logic building
