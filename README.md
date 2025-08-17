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
![Survival Count](https://github.com/aartimadole/-Titanic-Data-Analysis-Project/tree/b6046d4478e0408e5fc71b4b5fd8c3e7c872d973/Titanic%20python%20project/plots%20images)

### 2. Survival by Gender
![Survival by Gender][Titanic python project/plots images/survival_by_gender.png](https://github.com/aartimadole/-Titanic-Data-Analysis-Project/blob/3864c5bd55442182b38ae554e1574ba38210550f/Titanic%20python%20project/plots%20images/survival_by_gender.png)

### 3. Survival by Passenger Class
![Survival by Class](https://github.com/aartimadole/-Titanic-Data-Analysis-Project/blob/1bdd00b537df128f37ab971d7710ce7a83e53ba2/Titanic%20python%20project/plots%20images/survival_by_class.png)


### 4. Age Distribution
![Age Distribution](https://github.com/aartimadole/-Titanic-Data-Analysis-Project/blob/de96dd03506eb242e3fafd098bc93c7132066533/Titanic%20python%20project/plots%20images/age_distribution.png)


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
   git clone  https://github.com/aartimadole/-Titanic-Data-Analysis.git
