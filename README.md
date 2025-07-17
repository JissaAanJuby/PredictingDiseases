# 🏥 Disease Prediction System using Machine Learning

This is a Tkinter-based GUI application built with Python that predicts diseases based on symptoms entered by the user. It uses three machine learning algorithms: **Naive Bayes**, **Decision Tree**, and **Random Forest**. Users can also export prediction reports in CSV or PDF format.

---

## 📌 Project Features

- 🔘 User-friendly GUI using **Tkinter**
- 🧠 Predicts disease based on **five symptoms**
- ✅ Implements **Naive Bayes**, **Decision Tree**, and **Random Forest** classifiers
- 📊 Displays **model accuracy**
- 📄 Allows exporting predictions to **CSV or PDF**
- 🔄 Clear/reset button to restart predictions
- 💾 Stores the **last prediction** for export

---

## ⚙️ Requirements

Install dependencies using pip:

```bash
pip install pandas scikit-learn reportlab
```

---

## 🏃 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/disease-predictor.git
cd disease-predictor
```

2. Run the application:

```bash
python main.py
```

3. Select symptoms and click one of the model buttons (`NaiveBayes`, `DecisionTree`, `RandomForest`)

4. View the predicted disease and model accuracy.

5. Click `Export Report` to save the result as CSV or PDF.

---

## 🧾 Exported Report Format

The exported report (CSV or PDF) includes:

- Patient Name
- Selected Symptoms
- Predicted Disease
- Model Used
- Model Accuracy

Example:

```yaml
Name: Jissa Aan Juby
Symptom1: fatigue
Symptom2: headache
Symptom3: nausea
Symptom4: muscle_pain
Symptom5: fever
Predicted Disease: Dengue
Model Used: Naive Bayes
Accuracy: 92.13%
```

---

## 📸 GUI Screenshots

You can add screenshots like:

- GUI homepage
- Model prediction in action
- Export success message

---

## 🧠 Dataset Info

You must provide a dataset of symptoms and diseases. Each row corresponds to a case, with:

- **Input**: Symptoms (as binary features or encoded categories)
- **Output**: Disease label

Make sure to prepare training (`X`, `y`) and test sets (`X_test`, `y_test`) before using the model.

---

## 🔐 Future Improvements

- 🌐 Web version using Flask or Django
- 📱 Mobile app version
- 💾 Connect with SQL/NoSQL DB for persistent storage
- 📈 Confusion matrix and ROC curve visualization
- 🔁 Auto-retrain option for models with new data

---

## 👩‍💻 Developed By

**Jissa Aan Juby**  
Specialization: CSE with Data Science  
Project guided with help from ChatGPT-4  
GitHub: [@yourusername](https://github.com/yourusername)

---

## 📜 License

This project is licensed under the **MIT License**.
