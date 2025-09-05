# 🌧️ Rain Prediction using Machine Learning

This project predicts **whether it will rain tomorrow** using historical weather data from the **Australian Weather Dataset (weatherAUS.csv)**.  
It applies **data preprocessing, exploratory data analysis (EDA), and machine learning models** to build a predictive system.

---

## 📂 Project Structure
```
Rain_prediction/
│-- RainPred.ipynb        # Main Jupyter Notebook (model training & testing)
│-- weatherAUS.csv        # Dataset used for training/testing
│-- REQUIRMENTS.txt       # Dependencies file
│-- README.md             # Project documentation
```

---

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AbhiinavBhardwaj/Rain_Prediction.git
   cd Rain_Prediction
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r REQUIRMENTS.txt
   ```

---

## 📊 Dataset
- **Source**: Australian Bureau of Meteorology  
- **File**: `weatherAUS.csv`  
- **Target Variable**: `RainTomorrow` (Yes/No)

---

## 🧠 Models Implemented
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting (optional)

---

## 🚀 How to Run
1. Open the notebook:
   ```bash
   jupyter notebook RainPred.ipynb
   ```
2. Run all cells to train and test the models.  
3. Check evaluation metrics like **accuracy, confusion matrix, and classification report**.

---

## 📈 Results
- The model achieves an accuracy of **~X%** (replace with your result).  
- Confusion matrix and precision/recall are included in the notebook.

---

## 📌 Future Improvements
- Hyperparameter tuning for better accuracy  
- Deploy model using **Streamlit / Flask**  
- Use deep learning for time-series weather prediction  

---

## 👨‍💻 Author
**Abhinav Bhardwaj**  
[GitHub](https://github.com/AbhiinavBhardwaj)
