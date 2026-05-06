# Data Science Task 1: Titanic Data Analysis

## 📌 Project Overview
This project involves performing **Exploratory Data Analysis (EDA)** and **Data Cleaning** on the famous Titanic dataset. The goal is to identify factors that influenced the survival probability of passengers.

## 🛠️ Tools & Libraries
- **Language:** Python
- **Libraries:** 
  - `Pandas`: For data manipulation and cleaning.
  - `Matplotlib` & `Seaborn`: For data visualization.
  - `NumPy`: For numerical operations.

## 📁 Dataset Description
The dataset contains information about the passengers on the Titanic, including:
- **Survived:** Survival (0 = No, 1 = Yes)
- **Pclass:** Ticket class (1, 2, or 3)
- **Sex:** Passenger gender
- **Age:** Age in years
- **SibSp:** Number of siblings/spouses aboard
- **Parch:** Number of parents/children aboard
- **Fare:** Passenger fare
- **Embarked:** Port of Embarkation (C, Q, S)

## 🚀 Key Steps Performed
1. **Data Cleaning:** 
   - Handled missing values in the `Age` column by using the median.
   - Dropped the `Cabin` column due to a high percentage of missing data.
   - Filled missing `Embarked` values with the mode.
2. **EDA (Exploratory Data Analysis):**
   - Analyzed the survival rate based on Gender and Passenger Class.
   - Visualized the age distribution of passengers using histograms.
3. **Data Visualization:**
   - Created Heatmaps to check for correlations.
   - Used Bar Charts to compare survivors vs. non-survivors.

## 📊 Insights Found
- **Gender:** Females had a significantly higher survival rate than males.
- **Class:** Passengers in 1st Class were more likely to survive compared to those in 3rd Class.
- **Age:** Children had a higher priority for rescue, visible in the age distribution of survivors.

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Srushti0109/DataScience_Task1.git](https://github.com/Srushti0109/DataScience_Task1.git)
