# User Churn Prediction

This repository provides a comprehensive workflow for predicting user churn based on behavioral data. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, machine learning model training, and insights for actionable recommendations.

## Requirements

### Prerequisites
Ensure you have the following software installed on your system:
- Python 3.8 or higher
- Git

### Python Libraries
The following Python libraries are required:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install the required libraries by running:

```bash
pip install -r requirements.txt
```

## Setup and Execution

### Clone the Repository
```bash
git clone https://github.com/SasiVenkatGowdDasari/User_Churn_Prediction.git
cd User_Churn_Prediction
```

### Data Preparation
1. Place the dataset file (e.g., `events.csv`) in the root directory of the project.
2. Ensure the dataset has the expected columns: `event_time`, `event_type`, `product_id`, `category_id`, `category_code`, `brand`, `price`, `user_id`, and `user_session`.

### Running the Code

1. **Data Inspection & Preprocessing**:
   - Open `User_Churn_Prediction.ipynb` using Jupyter Notebook or JupyterLab.
   - Run the cells in sequence to load and preprocess the dataset.
   - This step includes handling missing values, duplicates, and feature transformations.

   ```bash
   jupyter notebook User_Churn_Prediction.ipynb
   ```

2. **Exploratory Data Analysis (EDA)**:
   - Visualize trends and distributions of key features like event types, popular brands, and categories.
   - Generate insights to understand user behavior better.

3. **Feature Engineering**:
   - Execute cells that calculate metrics like total spending, active days, and churn labels.
   - This step prepares the data for machine learning models.

4. **Model Training**:
   - Train and evaluate Logistic Regression and Random Forest models.
   - Compare performance metrics such as precision, recall, and F1-score.

5. **Visualization and Insights**:
   - Review feature importance, boxplots, and churn distributions.
   - Interpret the results and validate the recommendations.

### Key Output Files
- No explicit output files are saved by default. Modify the code in `User_Churn_Prediction.ipynb` to save intermediate or final results, if needed.

### Recommendations
At the end of the notebook, actionable insights and strategies for churn reduction are summarized based on the analysis.


## Repository Structure
```plaintext
User_Churn_Prediction/
│
├── User_Churn_Prediction.ipynb   # Main notebook for analysis and modeling
└── README.md                     # Documentation (this file)
```


Sasi Venkat Gowd Dasari
