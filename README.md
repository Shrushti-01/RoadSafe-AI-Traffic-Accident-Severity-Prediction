🚦 RoadSafe AI – Traffic Accident Severity Prediction & Analytics

Machine Learning-Based Indian Road Accident Analysis and Severity Prediction

RoadSafe AI is a machine learning-based project designed to analyze Indian road accident data, identify accident patterns, and predict accident severity based on various road, traffic, weather, and environmental conditions.

The project combines exploratory data analysis, machine learning models, and an interactive Gradio dashboard to make road accident data easier to understand and explore.

📌 Project Overview

Road accidents are influenced by several factors, including weather conditions, road types, traffic density, visibility, and vehicle involvement.

RoadSafe AI uses historical and synthetically expanded accident data to explore these factors and predict accident severity into three categories:

🟢 Minor

🟠 Major

🔴 Fatal

The project also provides visual insights into accident distributions and relationships between different accident-related factors.

🎯 Objectives

Analyze Indian road accident patterns.

Identify relationships between weather, road conditions, and accident severity.

Perform exploratory data analysis (EDA).

Apply machine learning classification algorithms.

Compare model performance using classification metrics.

Predict accident severity based on user-provided conditions.

Develop an interactive analytics dashboard using Gradio.

📊 Dataset Information

Dataset: Indian Roads Accident Dataset

Attribute

Details

Original records

20,000

Expanded records

30,000

Features

25

Target variable

accident_severity

Classes

Minor, Major, Fatal

Dataset Features

The dataset contains information related to:

City and State

Weather conditions

Road type

Traffic density

Accident cause

Day of the week

Hour of accident

Vehicles involved

Visibility

Temperature

Number of lanes

Traffic signals

Weekend and peak-hour indicators

Festival information

Accident severity

Data Transparency: The expanded dataset contains 20,000 original records and 10,000 synthetically generated records. Synthetic records are not verified real-world accident reports. The data_origin column distinguishes original and synthetic records.

⚙️ Technologies Used

Technology

Purpose

Python

Programming language

Pandas

Data manipulation

NumPy

Numerical operations

Matplotlib

Data visualization

Seaborn

Statistical visualization

Scikit-learn

Machine learning

Gradio

Interactive dashboard

Google Colab

Development environment

🤖 Machine Learning Approach

The project follows these major steps:

Data Loading

Data Cleaning and Preprocessing

Exploratory Data Analysis

Feature Selection

Categorical Encoding

Model Training

Model Comparison

Accuracy Evaluation

Accident Severity Prediction

The classification models and their actual results are available in the project notebook.

Evaluation Metrics

The models are evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

📈 Dashboard Features

RoadSafe AI includes an interactive Gradio dashboard with multiple sections.

1. Overview

Dataset summary

Accident severity distribution

Important project insights

2. Model Comparison

Comparison of machine learning models

Accuracy and other classification metrics

Best-performing model summary

3. Accident Analysis

Weather-wise accident severity analysis

Road-type-wise accident severity analysis

Visual exploration of accident patterns

4. Predict Accident Severity

Users can enter accident-related conditions such as:

City

State

Weather

Road type

Traffic density

Accident cause

Day of the week

Time of accident

Vehicles involved

Visibility

Temperature

Number of lanes

Traffic signal availability

Weekend and peak-hour conditions

Festival information

The trained model predicts the likely accident severity and displays class probabilities when supported by the selected model.

🚀 How to Run the Project

Step 1: Clone the Repository

git clone https://github.com/YOUR-USERNAME/RoadSafe-AI.git

Step 2: Navigate to the Project Folder

cd RoadSafe-AI

Step 3: Install Dependencies

pip install -r requirements.txt

Step 4: Open the Notebook

Open RoadSafe_AI_Dashboard.ipynb in Google Colab or Jupyter Notebook.

Step 5: Upload the Dataset

Upload indian_roads_dataset.csv when requested by the notebook.

Step 6: Run All Cells

Execute the notebook cells sequentially to preprocess the dataset, train the models, generate visualizations, and launch the Gradio dashboard.

📁 Project Structure

RoadSafe-AI/
│
├── RoadSafe_AI_Dashboard.ipynb
│
├── indian_roads_dataset.csv
│
├── indian_roads_dataset_original.csv
│
├── README.md
│
├── requirements.txt
│
└── .gitignore

🔮 Future Scope

Integration of verified real-world Indian road accident datasets.

Real-time traffic and weather data integration.

Geographic accident hotspot visualization.

Advanced feature engineering.

Improved model generalization using independent test datasets.

Interactive maps for accident-prone locations.

Deployment as a web-based road safety analytics platform.

⚠️ Limitations

The expanded dataset includes synthetic records.

Predictions depend on the quality and representativeness of the available data.

Model performance on this dataset may not represent performance on real-world accident records.

The system is intended for academic and analytical purposes, not emergency or official road-safety decisions.

For reliable evaluation, synthetic augmentation should be restricted to the training data, while testing should use untouched original records.

👩‍💻 Project Information

Project Name: RoadSafe AI
Domain: Artificial Intelligence & Machine Learning
Category: Traffic Accident Severity Prediction
Development Environment: Google Colab
Dashboard Framework: Gradio

⭐ Acknowledgement

This project was developed as an academic machine learning project to explore road accident patterns and demonstrate the application of data science and machine learning in road safety analytics.

If you find this project interesting, consider giving the repository a ⭐.
