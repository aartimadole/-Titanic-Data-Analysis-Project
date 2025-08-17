                                                              # -Titanic-Data-Analysis-Project
Titanic Survival Analysis using Python | pandas, NumPy, Seaborn, matplotlib Exploratory data analysis and feature engineering on the Titanic dataset to uncover survival patterns. Includes visual insights, correlation heatmaps, and custom features like Title and FamilySize. Ideal for showcasing Python-based data storytelling and analytical thinking.


# 🛳 Titanic Data Analysis Project

## 📌 Project Overview
This project analyzes the **Titanic dataset** to uncover insights about passenger survival rates.  
Using **Python**, **pandas**, **NumPy**, **Matplotlib**, and **Seaborn**, the project covers:
- Data loading and cleaning
- Exploratory Data Analysis (EDA)
- Data visualization
- Insights from the dataset

---

## 📂 Dataset
The dataset contains information about 891 passengers, including:
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1, 2, 3)
- **Sex**: Gender
- **Age**: Age in years
- **Fare**: Ticket fare
- **Embarked**: Port of embarkation
- And more…

---

## ⚙️ Technologies Used
- **Python**
- **pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

## 🧹 Data Cleaning
- Filled missing `Age` values with the median.
- Filled missing `Embarked` values with the mode.
- Dropped the `Cabin` column (too many missing values).

---

## 📊 Visualizations
Below are the visualizations generated in the project:

### 1. Survival Count
![Survival Count]("E:\Titanic python project\survival _count.png")

### 2. Survival by Gender
![Survival by Gender](images/survival_by_gender.png)

### 3. Survival by Passenger Class
![Survival by Class](images/survival_by_class.png)

### 4. Age Distribution
![Age Distribution](images/age_distribution.png)

### 5. Age vs Survival
![Age vs Survival](images/age_vs_survival.png)

### 6. Fare Distribution
![Fare Distribution](images/fare_distribution.png)

### 7. Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

---

## 📈 Key Insights
- **Females** had a significantly higher survival rate than males.
- **First-class passengers** had better chances of survival than second and third class.
- Younger passengers had slightly better survival odds.
- Higher ticket fares correlated with higher survival probability.

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-data-analysis.git

