# House-Rent-Prediction

## Introduction
The **House Rent Prediction** project leverages data analysis and machine learning to forecast residential rental prices. As the real estate market expands, finding reasonable and accurate rental prices becomes challenging for tenants and property owners. This project employs historical data and sophisticated algorithms to develop a predictive model that estimates rental costs based on various factors.

## Objective
Our project utilizes **Linear Regression**, a fundamental machine learning technique, to predict rental prices. The goal is to empower individuals and landlords with data-driven insights for informed decision-making in the housing market. The model predicts rent based on key property attributes such as:

- **Size of the house**
- **Floor level**
- **City location**
- **Furnishing status**
- **Number of bathrooms**

## Methodology
1. **Data Collection**  
   - We obtained a comprehensive dataset from Kaggle containing relevant features for rent prediction.
   
2. **Data Cleaning**  
   - Removed unnecessary data and handled missing values.
   - Identified and treated outliers.
   - Eliminated duplicate entries to ensure data integrity.

3. **Exploratory Data Analysis (EDA)**  
   - Performed statistical analysis and visualized distributions using histograms, boxplots, violin plots, and probability plots.
   - Conducted a rent comparison across major cities like Chennai, Delhi, and Bangalore, identifying key trends.

4. **Feature Engineering**  
   - Processed the 'Floor' column by splitting it into 'Floor Level' and 'Total Floors'.
   
5. **Splitting Data into Training and Testing Sets**  
   - Partitioned the dataset into training and testing subsets to evaluate model generalization.
   
6. **Building and Training the Model**  
   - Employed **Linear Regression** to model the relationship between independent variables and rental prices.
   - Adjusted model coefficients iteratively to minimize errors.
   
7. **Model Evaluation**  
   - Generated final predictions using an ensemble of models.
   - Evaluated performance using metrics like **Root Mean Squared Error (RMSE)** and **R-squared (R²)**.

## Results
The final model evaluation yielded the following metrics:
- **RMSE**: 50,480.63
- **R² Score**: 0.549

### Visualizations
- **Actual vs Predicted Rent Scatter Plot**: Showcases model performance across different rent levels.
- **Prediction Error Distribution**: Histogram and kernel density plot illustrate the spread of prediction errors.

## Resources Used
- **Kaggle**: Used for dataset acquisition.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/house-rent-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd house-rent-prediction
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script to train and test the model.

