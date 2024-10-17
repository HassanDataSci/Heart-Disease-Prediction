# Heart Disease Prediction Project

## Project Overview
This project is part of my Data Mining class, where I am working on predicting heart disease using machine learning models. The dataset consists of medical features such as age, cholesterol levels, chest pain type, and other factors that could indicate the likelihood of heart disease (0 = No, 1 = Yes).

## Dataset Description
The dataset from Kaggle contains 14 features and one target variable:
- **Age**: Age of the patient in years.
- **Sex**: Gender of the patient (1 = Male, 0 = Female).
- **Chest_Pain**: Type of chest pain (1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic).
- **Rest_BP**: Resting blood pressure (in mm Hg).
- **Cholesterol**: Serum cholesterol in mg/dl.
- **Fasting_BS**: Fasting blood sugar (> 120 mg/dl, 1 = True, 0 = False).
- **Rest_ECG**: Resting electrocardiographic results (0 = normal, 1 = ST-T wave abnormality, 2 = left ventricular hypertrophy).
- **Max_HR**: Maximum heart rate achieved.
- **Ex_Angina**: Exercise-induced angina (1 = Yes, 0 = No).
- **ST_Depression**: ST depression induced by exercise relative to rest.
- **Slope**: The slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping).
- **Vessel_Count**: Number of major vessels (0-3).
- **Thalassemia**: Blood disorder (3 = normal, 6 = fixed defect, 7 = reversible defect).
- **Target**: Heart disease indicator (1 = Yes, 0 = No).

## Current Progress
So far, I have worked on:
- **Exploratory Data Analysis (EDA)**: Explored the relationships between features using visualizations such as heatmaps, scatter plots, and distribution plots.
- **Data Cleaning**: Cleaned the dataset, handled missing values, and transformed categorical variables into numerical form.
- **Feature Engineering**: Analyzed correlations and selected important features for model training.

## Next Steps
I plan to implement various machine learning models to predict heart disease:
- **Decision Trees**
- **Logistic Regression**
- **Random Forests**
- **K-Nearest Neighbors (KNN)**

I’ll evaluate these models using metrics such as accuracy, precision, recall, and the AUC-ROC curve.

## Installation and Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Heart-Disease-Prediction.git
    cd Heart-Disease-Prediction
    ```

2. **Install the required libraries**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the analysis**:
    ```bash
    python heart_disease_analysis.py
    ```

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

You can install these dependencies using the `requirements.txt` file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
