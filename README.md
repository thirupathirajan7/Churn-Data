# Customer Churn Prediction

## Overview
This project builds a **Customer Churn Prediction** model using the Telco Customer Churn dataset. The notebook performs data preprocessing, exploratory data analysis (EDA), feature encoding, feature scaling, model training, and evaluation using a Random Forest classifier.

## Features
- Load and inspect customer churn dataset
- Data cleaning and preprocessing
- Handle missing values
- Encode categorical variables
- Scale numerical features
- Train a Random Forest classification model
- Evaluate model accuracy

## Dataset
The project uses the **Telco Customer Churn** dataset.

Dataset file:
```
WA_Fn-UseC_-Telco-Customer-Churn.csv
```

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

### 1. Import Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn

### 2. Load Dataset
Reads the Telco Customer Churn CSV file into a Pandas DataFrame.

### 3. Exploratory Data Analysis
- View dataset information
- Check missing values
- Generate descriptive statistics
- Visualize churn distribution

### 4. Data Preprocessing
- Convert `TotalCharges` to numeric
- Replace missing values with the median
- Encode categorical variables using `LabelEncoder`

### 5. Feature Engineering
- Separate features and target
- Remove `customerID`
- Split data into training and testing sets (80:20)

### 6. Feature Scaling
Standardize numerical features using `StandardScaler`.

### 7. Model Training
Train a **Random Forest Classifier** on the processed training data.

### 8. Model Evaluation
Evaluate the model using **Accuracy Score**.

## Project Structure

```
Customer-Churn-Prediction/
│
├── Churn_data.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Move into the project directory:

```bash
cd Customer-Churn-Prediction
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Churn_data.ipynb
```

Run all notebook cells.

## Output
The notebook displays:
- Dataset summary
- Missing value analysis
- Churn distribution plot
- Model accuracy

Example:

```
Model Accuracy: 0.80
```

*(Actual accuracy may vary because the Random Forest classifier uses randomness unless a fixed `random_state` is specified.)*

## Future Improvements
- Hyperparameter tuning
- Compare multiple machine learning algorithms
- Cross-validation
- Feature importance visualization
- Precision, Recall, F1-score, and ROC-AUC evaluation
- Model deployment using Flask or Streamlit

## License
This project is intended for educational and learning purposes.
