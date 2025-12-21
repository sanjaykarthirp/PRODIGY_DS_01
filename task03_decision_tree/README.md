
---

## 📊 Dataset Description

The dataset contains customer demographic information, banking details, and marketing campaign data.

| Column        | Description |
|---------------|-------------|
| age           | Customer age |
| job           | Type of job |
| marital       | Marital status |
| education     | Education level |
| balance       | Account balance |
| housing       | Housing loan status |
| loan          | Personal loan status |
| contact       | Contact communication type |
| duration      | Last contact duration |
| campaign      | Number of contacts during campaign |
| previous      | Previous contacts |
| poutcome      | Previous campaign outcome |
| y             | Target variable (yes/no) |

---

## 🧠 Steps Performed

### 1. **Data Loading**
- Loaded the dataset from `data/bank_marketing.csv`.

### 2. **Data Preprocessing**
- Applied **Label Encoding** to convert categorical variables into numerical form.
- Checked dataset structure and missing values.

### 3. **Model Training**
- Split dataset into train–test sets.
- Used **DecisionTreeClassifier** with `max_depth=4` to prevent overfitting.

### 4. **Model Evaluation**
- Evaluated using:
  - Accuracy Score
  - Classification Report (Precision, Recall, F1-score)

### 5. **Model Visualization**
- Plotted a Decision Tree using Matplotlib’s `plot_tree()`.

---

## 📈 Model Performance

The model performed well on the test set:

- **Accuracy:** 100% (Note: The dataset is very small, so accuracy may seem unusually high.)

---

## 🖼 Decision Tree Visualization

The notebook generates a graphical representation of the decision tree showing data splits, feature importance, and classification paths.

---

## 🚀 Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  

---

## 📌 How to Run

```bash
# Navigate to the folder
cd task03_decision_tree

# Open Jupyter Notebook
jupyter notebook
