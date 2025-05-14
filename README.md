# Microsoft-Edunet-AICTE

# 📊 Loan Default Prediction

This project builds a machine learning model to predict whether a loan will be fully paid or not using a Decision Tree Classifier. It covers data preprocessing, visualization, cross-validation, and hyperparameter tuning using GridSearchCV.

---

## 📁 Dataset

The dataset used is `loan_data.csv`, containing 9578 records and 14 attributes, including:

- `credit.policy`
- `purpose`
- `int.rate`
- `installment`
- `log.annual.inc`
- `dti`
- `fico`
- `days.with.cr.line`
- `revol.bal`
- `revol.util`
- `inq.last.6mths`
- `delinq.2yrs`
- `pub.rec`
- `not.fully.paid` *(Target Variable)*

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧱 Project Structure

### 1. Data Loading & Exploration
- Reading the dataset
- Checking for null values, data types, and statistical summary
---

### 2. Data Preprocessing
- Label Encoding categorical features (`purpose`)
- Splitting dataset using `train_test_split`
---

### 3. Data Visualization
- Histograms for FICO scores
- Countplot for loan purpose vs payment status
- Jointplot: FICO vs Interest Rate
- Correlation Heatmap

### 4. Modeling
- Stratified K-Fold Cross Validation
- Decision Tree Classifier
- Hyperparameter tuning (`max_depth`) using `GridSearchCV`

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

---

## 🧪 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/loan-default-prediction.git
   cd loan-default-prediction


2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script or notebook**:

   * Open `loan_default_prediction.ipynb` in Jupyter Notebook
   * Or run the `.py` script if available

---

## ✅ Output Highlights

* Optimal tree depth selected via `GridSearchCV`
* Model evaluated on test data with classification report
* Visualization of prediction accuracy and important features

---

## 📌 Key Learnings

* How to preprocess real-world data
* Handling categorical variables in machine learning
* Visual data analysis to extract patterns
* Using cross-validation to generalize better
* Hyperparameter tuning using `GridSearchCV`

---

## 📷 Sample Visualizations

![image](https://github.com/user-attachments/assets/70547fbc-47d2-4911-967b-f24e7a506a48)

![image](https://github.com/user-attachments/assets/b4c7a68f-2b80-4ce4-a3c8-fdb2a2bc51fb)

![image](https://github.com/user-attachments/assets/c84ae7e2-ab9e-4ed6-921b-e2c6c4f5a3a0)

![image](https://github.com/user-attachments/assets/af1300dd-8f0b-48bb-a8af-a360a5362540)

![image](https://github.com/user-attachments/assets/5fdad90b-277d-4fe9-8151-27c77f40d722)


---



⭐️ **Star this repository** if you found it helpful!

```

Let me know your GitHub username and repo name if you'd like me to personalize the links or add badges like `License`, `Last Commit`, etc.
```
