# 💧 Smart Water Quality Prediction & Monitoring System

### Machine Learning Based Water Quality Classification and Monitoring

---

## 📌 Project Overview

The Smart Water Quality Prediction & Monitoring System is a Machine Learning-based project developed to analyse water quality parameters and classify water into three categories: Safe, Moderate, and Unsafe.

The system uses multiple Machine Learning classification algorithms to predict water quality based on input parameters. It also provides an interactive dashboard to display predictions, analyse water quality conditions, and support monitoring.

## 🎯 Project Objectives

- Develop a Machine Learning-based water quality classification system.
- Analyse multiple physical and operational water parameters.
- Identify potentially unsafe water conditions.
- Train and evaluate different classification models.
- Compare model performance and select the best-performing model.
- Provide an interactive dashboard for water quality prediction and monitoring.

## ⚙️ Input Parameters

The system considers the following water quality parameters:

- pH Level
- Turbidity
- Total Dissolved Solids (TDS)
- Flow Rate
- Pressure
- Temperature
- Daily Water Usage
- Days Since Filter Change

## 🤖 Machine Learning Algorithms

The following classification algorithms are evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. AdaBoost

### Hyperparameter Optimization

GridSearchCV is used for hyperparameter optimization to improve model performance.

## 📊 Model Performance

The following results are reported in the project poster:

| Machine Learning Model | Accuracy |
|---|---:|
| Logistic Regression | 70.42% |
| Decision Tree | 95.42% |
| Random Forest | 94.17% |
| AdaBoost | 88.75% |

### Final Selected Model

- Selected Model: Tuned Decision Tree
- Reported Test Accuracy: 97.08%
- Best GridSearchCV Score: 96.25%

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Gradio
- Machine Learning

## ✨ Key Features

- Water quality classification into Safe, Moderate, and Unsafe categories.
- Multiple parameter-based water quality analysis.
- Machine Learning model comparison.
- Hyperparameter tuning using GridSearchCV.
- Prediction probabilities and classification results.
- Interactive water quality dashboard.
- Batch processing of water quality records.
- Model evaluation using a confusion matrix.

## 🔄 Project Methodology

1. Input water quality parameters.
2. Data collection and preprocessing.
3. Machine Learning model training.
4. Model evaluation and comparison.
5. Best model selection.
6. Water quality prediction.
7. Dashboard-based monitoring and result visualisation.

## 📁 Repository Contents

- `Smart_Water_Quality_Prediction.ipynb` – Jupyter Notebook containing the Machine Learning workflow.
- `water_purification_dataset.csv` – Dataset file used for the project.
- `Poster.jpeg` – Project poster presenting the methodology, model comparison, and results.
- `README.md` – Project documentation.

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/aayushidehankar20/Smart-Water-Quality-Prediction-System.git
```

### Step 2: Open the Project Folder

```bash
cd Smart-Water-Quality-Prediction-System
```

### Step 3: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter streamlit gradio
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Smart_Water_Quality_Prediction.ipynb` and execute the notebook cells.

Note: The dataset must have the columns and target labels expected by the notebook. Additional dashboard modules or saved model files may be required for running the complete application.

## 📈 Project Outcome

The project demonstrates the application of Machine Learning techniques in water quality classification. The selected tuned Decision Tree model achieved a reported test accuracy of 97.08%.

The dashboard presents prediction results and supports the analysis of water quality records.

## 🔮 Future Scope

- Integration with IoT-based water quality sensors.
- Real-time water quality monitoring.
- Cloud-based data storage and monitoring.
- Larger and more diverse datasets for model validation.
- Mobile application integration.
- Continuous monitoring and automated alerts.

## 👩‍💻 Project Author

**Aayushi Dehankar**

Project Domain: Machine Learning | Data Science | Water Quality Monitoring

**Ramdeobaba University, Nagpur**

Department of Computer Science and Engineering

---

*Developed as an academic Machine Learning project.*

