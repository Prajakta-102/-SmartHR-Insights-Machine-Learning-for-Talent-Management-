## 📘 Project Title: SmartHR Insights – Machine Learning for Talent Management

---

### 📌 Problem Statement

Your client is a large MNC with 9 broad verticals across the organization. One of the key challenges is **identifying the right candidates for promotion** (only for manager position and below) and preparing them in time.

The promotion process currently includes recommendations, evaluations, training, and final assessments — but it is **time-consuming** and delays internal transitions. This project aims to **predict promotion eligibility early** using machine learning, based on historical HR data.

---

### 🎯 Objective

To build a classification model that predicts whether an employee is likely to be promoted using features such as performance scores, training history, demographic data, and more.

---

### ✅ Key Goals

- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA) to extract insights.
- Handle class imbalance using SMOTE.
- Train and compare various classification models.
- Tune the best model for optimal performance.
- Evaluate model performance with appropriate metrics.
- Apply the model on unseen test data to assist the HR team.

---

### 🛠️ Algorithms Used

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **✅ Random Forest Classifier** *(Final model)*

---

### 🔧 Hyperparameter Tuning (Random Forest)

| Parameter              | Value |
|------------------------|-------|
| `n_estimators`         | 100   |
| `max_depth`            | 10    |
| `min_samples_split`    | 10    |
| `min_samples_leaf`     | 5     |

---

### 📊 Evaluation Techniques

- **Data Split**: 70% Training / 30% Testing (`random_state=10`)
- **Imbalance Handling**: SMOTE
- **Evaluation Metrics**:
  - Accuracy ✅
  - F1 Score ✅ *(Primary metric due to class imbalance)*
  - Confusion Matrix
  - Classification Report

---

### 📈 Final Model Performance

| Model               | Accuracy     | F1 Score (approx) |
|---------------------|--------------|-------------------|
| Logistic Regression | ~78.9%       | 0.47              |
| Decision Tree       | ~80.3%       | 0.50              |
| ✅ Random Forest     | **92.62%**   | **(check notebook for exact value)** |

---

### 📌 Important Features

Top contributing variables:

- Previous Year Rating
- KPIs Met > 80%
- Awards Won
- Average Training Score
- Length of Service
- Education Level
- Recruitment Channel
- Department
- No. of Trainings

---

### 📊 EDA Insights

- Higher **Previous Year Rating** and **KPI success** strongly correlate with promotions.
- Employees who won **awards** are significantly more likely to be promoted.
- **Sales & Marketing** had the highest number of promotions.
- Longer service doesn’t always mean promotion — performance matters more.

---

### 💼 Business Impact

- 🕒 **Faster HR Decisions**: Promotes data-driven, early identification of promotion candidates.
- 🎯 **Targeted Training**: Helps focus learning resources on the most eligible employees.
- 🧠 **Better Retention**: Boosts employee satisfaction through timely rewards.
- 🔄 **Scalable Model**: Adaptable across multiple departments and verticals.

---

### 🧾 Conclusion

This end-to-end machine learning solution enables HR teams to **predict employee promotions** with high accuracy (**92.62%**), reducing manual workload and promoting fairness in the process. The Random Forest model provides a solid foundation for internal mobility optimization and can be enhanced further with real-time data and automation.

---

### 👩‍💻 Author
Prajakta More
EXTC Engineer | Data Analyst | Aspiring Data Scientist
Power BI, Tableau & Python Enthusiast
Turning data into insights using ML, SQL, Excel & storytelling.
