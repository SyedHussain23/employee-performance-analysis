# ⭐ employee-performance-analysis

This project analyzes the **INX Future Inc. Employee dataset** to identify factors influencing employee performance and build a machine learning model to predict performance ratings.

It demonstrates an end-to-end ML pipeline including **EDA, feature engineering, modeling, evaluation, and business insights**.

---

## 📌 Project Overview

* **Problem Type:** Multi-class classification
* **Domain:** HR Analytics / Machine Learning
* **Target Variable:** `PerformanceRating`
* **Model Used:** Random Forest Classifier
* **Framework:** Scikit-learn

---

## 📊 Dataset

The dataset contains employee demographic, job, experience, satisfaction, and compensation attributes.

Key feature categories:

* Employee demographics
* Job role & department
* Experience & tenure
* Salary & job satisfaction metrics
* Work-life balance indicators

---

## 🔍 Exploratory Data Analysis (EDA)

EDA steps performed:

* Checked missing values and distributions
* Visualized performance rating distribution
* Examined relationships across departments and roles
* Correlation analysis for numerical features

### Key Insights

* Department and Job Role strongly influence performance
* Experience and tenure show strong predictive patterns
* Salary hike percentage correlates with performance
* Job involvement and distance from home impact outcomes

---

## 🔧 Feature Engineering

New features created:

* `ExperienceLevel`
* `YearsSinceLastEngagement`
* `IsManager`
* `ExperienceRatio`

---

## 🧠 Model Selection & Training

### Model Used: Random Forest Classifier

Reasons:

* Handles tabular HR data effectively
* Captures nonlinear relationships
* Robust with minimal tuning
* Provides feature importance insights

Pipeline:

* OneHotEncoding for categorical features
* Numerical passthrough
* Random Forest classifier

---

## 📈 Model Evaluation

### Test Performance

* **Accuracy:** 91.25%
* **Precision:** 91.66%
* **Recall:** 91.25%
* **F1-Score:** 90.78%

The model demonstrates strong and balanced predictive performance.

---

## ⭐ Key Findings

* Job Role & Department are strongest predictors
* Experience and tenure significantly influence performance
* Salary hike percentage is a major motivator
* Job involvement and work-life aspects affect outcomes

---

## 🤖 Example Prediction

The trained model can predict performance ratings for new employee profiles using structured feature inputs.

---

## 🛠️ Tech Stack

| Tool                 | Purpose          |
| -------------------- | ---------------- |
| Python               | Programming      |
| Pandas / NumPy       | Data processing  |
| Scikit-learn         | Machine learning |
| Matplotlib / Seaborn | Visualization    |
| Jupyter Notebook     | Experimentation  |

---

## 🚀 How to Run

```bash
git clone https://github.com/SyedHussain23/employee-performance-analysis.git
cd employee-performance-analysis
pip install -r requirements.txt
jupyter notebook employee-performance-analysis.ipynb
```

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Explainable AI (SHAP / LIME)
* HR analytics dashboard deployment
* Ensemble and boosting models
* Automated feature selection

---

## 👨‍💻 Author

**Syed Hussain Abdul Hakeem**

🔗 LinkedIn
[https://www.linkedin.com/in/syed-hussain-abdul-hakeem](https://www.linkedin.com/in/syed-hussain-abdul-hakeem)

🔗 GitHub
[https://github.com/SyedHussain23](https://github.com/SyedHussain23)

---

## 📄 License

This project is open source and available under the MIT License.

---

## ⭐ Show Your Support

If you found this project useful, consider giving it a ⭐ on GitHub.
