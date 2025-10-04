# 🏨 Hotel Booking Cancellation Prediction 📉

A comprehensive machine learning project to predict hotel booking cancellations and uncover key factors driving them.

---

### 📋 Project Overview

This project tackles the significant challenge of hotel booking cancellations, which lead to revenue loss and operational issues. By leveraging a real-world dataset, this analysis implements an end-to-end machine learning workflow to build a predictive model that can identify high-risk bookings. The goal is to empower hotel managers with data-driven tools to reduce cancellations and optimize revenue.

---

### ✨ Key Features

*   **🔍 In-Depth EDA**: Detailed exploratory data analysis with visualizations to understand booking trends and cancellation patterns.
*   **🧼 Data Cleaning**: Rigorous preprocessing including handling missing values and removing duplicate entries.
*   **🛠️ Feature Engineering**: Creation of new, insightful features like `total_stay_nights` and `is_returning_guest` to enhance model performance.
*   **🧠 Multi-Model Implementation**: Training and evaluation of multiple algorithms to find the most robust solution.
*   **📊 Performance Evaluation**: Comprehensive model assessment using metrics like Accuracy, F1-Score, Precision, Recall, and AUC, complete with confusion matrices and ROC curves.

---

### 💻 Technologies Used

*   **Python**: Core programming language for the analysis.
*   **Pandas & NumPy**: For data manipulation and numerical operations.
*   **Scikit-learn**: For data preprocessing and implementing machine learning models.
*   **TensorFlow**: For building and training the deep learning model.
*   **Matplotlib & Seaborn**: For data visualization.
*   **Jupyter Notebook**: As the interactive development environment.

---

### 🤖 Models Implemented

This project compares a diverse set of machine learning models:

1.  **Logistic Regression**: Serves as a strong linear baseline.
2.  **Random Forest Classifier**: An ensemble method for high accuracy and feature importance.
3.  **K-Means Clustering**: An unsupervised model to discover natural customer segments.
4.  **TensorFlow Neural Network**: A deep learning model to capture complex, non-linear patterns.

---

### 🚀 Results & Performance

The models were benchmarked to identify the most effective one for this prediction task.

*   🏆 **Best Performing Model**: **Random Forest Classifier**
    *   **Accuracy**: **84.1%**
    *   **F1-Score**: **74.2%**
