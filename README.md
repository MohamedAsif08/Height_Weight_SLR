# Height-Weight Linear Regression Analysis

This project demonstrates a simple linear regression model applied to predict height based on weight using a dataset. It includes essential data preprocessing, visualization, and model evaluation techniques.

---

## Features of the Project

1. **Data Loading**: The dataset (`Height_weight.xlsx`) is read from the `data` folder using the `pandas` library.  
2. **Visualization**:  
   - Scatter plot to visualize the relationship between height and weight.  
   - Correlation matrix for feature relationships.  
   - Seaborn pairplot for detailed visual exploration.  
3. **Data Splitting**: Train-test split with 75% of data for training and 25% for testing.  
4. **Standardization**: Scaling the data using `StandardScaler` for improved model performance.  
5. **Linear Regression Model**:  
   - Training the model to predict height based on weight.  
   - Evaluating the model with metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), \( R^2 \), and Adjusted \( R^2 \).  
6. **Visualization of Results**: Plotting the best-fit line for the training data.  
7. **Advanced Regression Analysis**: Using `statsmodels` for OLS regression and examining detailed regression statistics.

---

## Installation

### Prerequisites

Make sure you have Python and the required libraries installed.  
To install the necessary libraries, run:  

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels openpyxl
```

---

## Project Structure

```
Height_Weight_SLR/  
├── data/  
│   └── Height_weight.xlsx  
├── notebooks/  
│   └── height_weight_analysis.ipynb  
├── scripts/  
│   └── preprocessing.py (optional for extensions)  
└── README.md  
```

---

## How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Height_Weight_SLR.git
   ```

2. Navigate to the `notebooks` directory:  
   ```bash
   cd Height_Weight_SLR/notebooks
   ```

3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook height_weight_analysis.ipynb
   ```

4. Ensure the `Height_weight.xlsx` file is in the `data` folder relative to the project structure.

---

## Key Results

- **Slope (Coefficient)**: Shows the rate of change in height with weight.  
- **Intercept**: The predicted height when weight is zero.  
- **\( R^2 \) Score**: Measures how well the model explains the variance in the data.  
- **Adjusted \( R^2 \)**: Adjusts \( R^2 \) for the number of predictors in the model.

---

## Example Outputs

- **Scatter Plot**:  
  Visualizes the relationship between height and weight.  

- **Best-Fit Line**:  
  A regression line overlayed on the scatter plot.  

- **Metrics**:  
  - \( R^2 \): 0.85  
  - Adjusted \( R^2 \): 0.84  

---

## Future Work

1. Extend the analysis to multiple predictors (e.g., age, gender).  
2. Evaluate model performance with additional metrics.  
3. Deploy the model as an API for real-world applications.

---

## Author

- Mohamed Asif M 
- LinkedIn: [www.linkedin.com/in/mdasifm](https://www.linkedin.com/in/md-asif-m/)  
- GitHub:   https://github.com/MohamedAsif08

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

