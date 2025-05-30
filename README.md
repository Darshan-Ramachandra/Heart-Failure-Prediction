# Heart Failure Prediction Using Machine Learning :heart:

## Overview 🔍
A comprehensive machine learning project to predict heart failure events using clinical data. Built in a Jupyter Notebook with Python, this project explores data preprocessing, feature analysis, and compares multiple classification algorithms—highlighting how simple biomarkers like **serum creatinine** and **age** can drive accurate predictions.

## Key Insights 📈
Derived from our research paper:
- **Biomarkers**: Only **serum creatinine** and **age** are used, making the model easy to deploy in clinical settings.
- **Top Performance**:  
  - **Gradient Boosting** achieved the highest accuracy of **0.87**.  
  - **Random Forest** and **Naïve Bayes** also showed strong results (accuracy ≥ 0.84).  
- **Feature Importance**: Serum creatinine and age ranked as the most predictive features, confirmed via correlation and importance analyses.  
- **Clinical Implication**: Early detection of heart failure can significantly improve patient outcomes and reduce healthcare costs by focusing on routinely measured biomarkers.

## Features ✨
- **Data Loading & Preprocessing**  
  - Handles missing values, outliers, normalization, and train–test split (70:30).  
- **Exploratory Data Analysis**  
  - Correlation heatmap, age vs. patient count, gender distribution, and scatter plots.  
- **Model Comparison**  
  - Implements and evaluates:  
    - Support Vector Machines (Linear, Poly, RBF, Sigmoid)  
    - Logistic Regression  
    - Naïve Bayes  
    - K-Nearest Neighbors  
    - Decision Tree  
    - Random Forest  
    - AdaBoost  
    - Gradient Boosting  
    - Bagging Classifier  
- **Evaluation Metrics**  
  - Accuracy, Precision, Recall, F1-Score, Confusion Matrix.  
- **Visualization**  
  - Bar charts for algorithm accuracies, feature importance graphs, scatter plots.

## Technologies Used

| Technology            | Description                                                               |
|-----------------------|---------------------------------------------------------------------------|
| **Python 3.x**        | Core programming language for data processing and modeling                |
| **Jupyter Notebook**  | Interactive environment for experiment tracking and code documentation    |
| **pandas & NumPy**    | Data manipulation and numerical operations                                |
| **scikit-learn**      | Machine learning library for model implementation and evaluation          |
| **matplotlib**        | Plotting library for visualizations                                       |
| **seaborn**           | Statistical data visualization                                            |

## Installation 🛠️

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Darshan-Ramachandra/Heart-Failure-Prediction.git
   ```
2. **Navigate to the project directory**  
   ```bash
   cd heart-failure-ml
   ```
3. **Create and activate a virtual environment**  
   ```bash
   python3 -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```
4. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
5. **Download the dataset**  
   - Get the “Heart Failure Clinical Records” CSV from Kaggle:  
     https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data/data  
   - Place it in a `data/` folder at the project root:  
     ```
     data/heart_failure_clinical_records_dataset.csv
     ```
6. **Launch Jupyter Notebook**  
   ```bash
   jupyter notebook Heart_Failure_Prediction.ipynb
   ```

## Usage 🚀
1. **Open** `Heart_Failure_Prediction.ipynb` in Jupyter.  
2. **Run** each cell sequentially to:
   - Load and preprocess data  
   - Visualize exploratory analyses  
   - Train and evaluate each ML model  
   - Examine key findings and feature importance  
3. **Modify** hyperparameters or add new algorithms as desired.

## Contributing 🤝
1. **Fork** the repository.  
2. **Clone** your fork:  
   ```bash
   git clone https://github.com/Darshan-Ramachandra/Heart-Failure-Prediction.git
   ```
3. **Create** a feature branch:  
   ```bash
   git checkout -b feature-name
   ```
4. **Commit** your changes:  
   ```bash
   git add .
   git commit -m "Add descriptive message"
   ```
5. **Push** to your branch:  
   ```bash
   git push origin feature-name
   ```
6. **Open** a Pull Request against `main` and discuss improvements.

## License 📄
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
