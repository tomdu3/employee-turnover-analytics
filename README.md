# Employee Turnover Analytics

This project aims to develop machine learning models and techniques to analyze employee turnover at Portobello Tech, an app innovator company, using Jupyter Notebooks. The primary objectives are:

1. **Data Quality Checks**: Perform data quality checks by identifying and handling missing values, if any.
2. **Exploratory Data Analysis (EDA)**: Understand the factors that contribute most to employee turnover through EDA.
3. **Clustering Analysis**: Perform clustering of employees who left the company based on their satisfaction and evaluation scores.
4. **Class Imbalance Handling**: Handle the class imbalance issue in the employee turnover data using the SMOTE (Synthetic Minority Over-sampling Technique) technique.
5. **Model Training and Evaluation**: Perform k-fold cross-validation for model training and evaluate the performance of different machine learning models using appropriate evaluation metrics.
6. **Best Model Identification**: Identify the best-performing model and justify the choice of evaluation metrics.
7. **Retention Strategies**: Suggest various retention strategies for targeted employees based on the analysis.

## Table of Contents

- [Installation](#installation)
- [Data](#data)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/tomdu3/employee-turnover-analytics.git
   ```

2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

3. Install Jupyter Notebook:
   ```
   pip install jupyter
   ```

## Data

The project uses employee data provided by Portobello Tech, which includes information such as the number of projects worked on, average monthly working hours, time spent in the company, promotions in the last five years, salary level, and employee satisfaction scores. The data is owned by the HR Department and will be used to predict employee turnover.

## Usage

1. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```

2. Open the relevant Jupyter Notebook files in the project directory:
   - `data_quality_checks.ipynb`
   - `eda.ipynb`
   - `clustering.ipynb`
   - `smote.ipynb`
   - `model_training.ipynb`
   - `best_model.ipynb`

3. Follow the instructions and code cells in each Notebook to perform the respective tasks.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
