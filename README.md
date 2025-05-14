# Microsoft-Edunet-AICTE
Sure! Below is the same `README.md` content, now formatted for GitHub with proper markdown syntax and code blocks:

````markdown
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

### 2. Data Preprocessing
- Label Encoding categorical features (`purpose`)
- Splitting dataset using `train_test_split`

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
````

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

> Include plots like heatmaps, jointplots, and histograms here using Markdown images or links.

---

## 📬 Contact

For any questions or suggestions, feel free to open an issue or reach out:

* [GitHub](https://github.com/your-username)
* Email: [your-email@example.com](mailto:your-email@example.com)

---

⭐️ **Star this repository** if you found it helpful!

```

Let me know your GitHub username and repo name if you'd like me to personalize the links or add badges like `License`, `Last Commit`, etc.
```
