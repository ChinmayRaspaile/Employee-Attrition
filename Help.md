# Help Guide for Employee Attrition Prediction Project

This guide provides an overview of the key steps and processes followed in the `ML_PROJECT_Employee_Attrition.ipynb` notebook. The notebook is structured to help predict employee attrition using data exploration and machine learning techniques.

## Steps Performed in the Notebook

### 1. Data Loading and Preparation
- **Load the Dataset**: The data is imported from a CSV file (`Employeeattrition.csv`) to a Pandas DataFrame.
- **Check for Missing Values**: Identifies any missing data and prepares the dataset for analysis.

### 2. Exploratory Data Analysis (EDA)
- **Visualize Attrition Count**: Uses a bar plot to display the count of employees who left or stayed.
- **Correlation Analysis**: Displays a correlation heatmap to explore relationships between numeric features.
- **Income and Attrition Plot**: A box plot shows the distribution of employee income based on attrition status.

### 3. Data Preprocessing
- **Encoding Categorical Features**: Converts categorical columns to numerical using one-hot encoding.
- **Feature Scaling**: Scales numerical features for consistent model performance using StandardScaler.

### 4. Model Training
- **Select and Train Model**: Trains a machine learning model (e.g., Decision Tree, Logistic Regression) to predict employee attrition based on features.
- **Train-Test Split**: Splits data into training and testing sets to evaluate model performance.

### 5. Model Evaluation
- **Performance Metrics**: Calculates accuracy and other metrics like precision, recall, and F1-score to evaluate model performance.

## How to Use the Notebook

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Employee-Attrition.git
