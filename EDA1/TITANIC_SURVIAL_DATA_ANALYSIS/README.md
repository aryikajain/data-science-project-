# Titanic Survival Data Analysis

### Project Overview  
The **Titanic Survival Analysis** explores which factors most strongly influenced a passenger’s chance of survival in the tragic 1912 disaster.  
Using data analysis, visualization, and feature engineering, this project aims to uncover **patterns and insights** in passenger demographics, ticket class, fare, and other variables.

---

###  Objectives  
- Understand the dataset structure and features.  
- Handle **missing values** and **outliers** effectively.  
- Explore how **gender, age, and passenger class** affected survival.  
- Perform **EDA (Exploratory Data Analysis)** and create **visual stories**.  
- Learn **feature encoding**, **correlation analysis**, and **data cleaning**.  
- (Optional) Build a **basic ML model** to predict survival outcomes.

---

###  Concepts Covered  
| Concept | Description |
|----------|--------------|
| **Missing Value Handling** | Using `fillna`, `dropna`, median/mode replacement |
| **Outlier Detection** | Using boxplots to identify extreme values |
| **Encoding Categorical Data** | Label & one-hot encoding for model readiness |
| **Correlation & Heatmap** | Finding relationships between features |
| **Visualization & Storytelling** | Using Seaborn & Matplotlib to uncover insights |
| **Feature Engineering** | Creating new features like `FamilySize` |

---

###  Key Questions Explored  
- Which features most affect survival?  
- Does **gender** or **passenger class** matter more?  
- How does **fare** influence survival probability?  
- What age groups were more likely to survive?  

---

#### Dataset  
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
- **Files Used:**  
  - `titanic.csv` (combined training and test data for EDA)  

---

### Tools & Libraries  
```
Python 3.x  
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn (optional for modeling)
```

---

### 📂 Project Structure  
```
Titanic-Survival-Analysis/
│
├── data/
│   └── titanic.csv
│
├── notebooks/
│   └── titanic_analysis.ipynb
│
├── visuals/
│   ├── survival_by_gender.png
│   ├── class_vs_survival.png
│   └── heatmap.png
│
├── scripts/
│   └── clean_and_encode.py
│
├── README.md
```

---

###  EDA Insights Summary  
| Insight | Observation |
|----------|--------------|
| **Gender** | Females had a much higher survival rate than males. |
| **Class** | Passengers in 1st class survived the most. |
| **Age** | Younger passengers had better chances of survival. |
| **Fare** | Higher fares correlated with higher survival probability. |
| **Family Size** | Moderate family size (2–4 members) had better survival. |

---

###  Steps Performed  
1. Loaded dataset & explored structure.  
2. Handled missing data (Age, Embarked).  
3. Detected and examined outliers in Fare.  
4. Encoded categorical columns (Sex, Embarked).  
5. Analyzed feature correlations.  
6. Created visualizations for storytelling.  
7. (Optional) Built a Logistic Regression model to test predictability.  

---

### Example Visuals  
- **Gender vs Survival Countplot**  
- **Pclass vs Survival Rate**  
- **Age & Fare Distribution**  
- **Correlation Heatmap**

---

###  Learnings  
- Gained understanding of **real-world data cleaning** techniques.  
- Learned to use **EDA and visualization** to tell a story with data.  
- Discovered how small preprocessing steps impact **model performance**.  
- Understood how to connect **insights → business or social meaning**.

---

### 🧩 Optional: Simple Model Accuracy Example
```python
Logistic Regression Accuracy: 0.79
```
*(Model built using basic cleaned features — not tuned)*

---

###  Future Improvements  
- Feature scaling & model tuning  
- Adding decision tree or random forest models  
- Comparing ML performance metrics  

---

###  Author  
**Aryika Jain**  
📍 Data Science & ML Enthusiast | Exploring AI, NLP & EDA  
🔗 [GitHub Profile](https://github.com/aryikajain)
