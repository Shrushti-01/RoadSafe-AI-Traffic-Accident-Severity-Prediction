# 🚦 RoadSafe AI – Traffic Accident Severity Prediction & Analytics

### Machine Learning-Based Indian Road Accident Analysis and Severity Prediction

RoadSafe AI is a machine learning-based project designed to analyze Indian road accident data, identify accident patterns, and predict accident severity based on various road, traffic, weather, and environmental conditions.

The project combines exploratory data analysis, machine learning models, and an interactive Gradio dashboard to make road accident data easier to understand and explore.

---

## 📌 Project Overview

Road accidents are influenced by several factors, including weather conditions, road types, traffic density, visibility, and vehicle involvement.

RoadSafe AI uses historical and synthetically expanded accident data to explore these factors and predict accident severity into three categories:

- 🟢 Minor
- 🟠 Major
- 🔴 Fatal

The project also provides visual insights into accident distributions and relationships between different accident-related factors.

---

## 🎯 Objectives

- Analyze Indian road accident patterns.
- Identify relationships between weather, road conditions, and accident severity.
- Perform exploratory data analysis (EDA).
- Apply machine learning classification algorithms.
- Compare model performance using classification metrics.
- Predict accident severity based on user-provided conditions.
- Develop an interactive analytics dashboard using Gradio.

---

## 📊 Dataset Information

**Dataset:** Indian Roads Accident Dataset

| Attribute | Details |
|---|---|
| Original records | 20,000 |
| Expanded records | 30,000 |
| Features | 25 |
| Target variable | `accident_severity` |
| Classes | Minor, Major, Fatal |

### Dataset Features

The dataset contains information related to:

- City and State
- Weather conditions
- Road type
- Traffic density
- Accident cause
- Day of the week
- Hour of accident
- Vehicles involved
- Visibility
- Temperature
- Number of lanes
- Traffic signals
- Weekend and peak-hour indicators
- Festival information
- Accident severity

**Data Transparency:** The expanded dataset contains 20,000 original records and 10,000 synthetically generated records. Synthetic records are not verified real-world accident reports. The `data_origin` column distinguishes original and synthetic records.

---

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning |
| Gradio | Interactive dashboard |
| Google Colab | Development environment |

---

## 🤖 Machine Learning Approach

The project follows these major steps:

1. Data Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Categorical Encoding
6. Model Training
7. Model Comparison
8. Accuracy Evaluation
9. Accident Severity Prediction

The classification models and their actual results are available in the project notebook.

### Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📈 Dashboard Features

RoadSafe AI includes an interactive Gradio dashboard with multiple sections.

### 1. Overview
