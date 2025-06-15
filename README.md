# house-price-prediction

Machine learning project to predict house prices based on features like area, location, number of bedrooms, and other property attributes.

## Dataset

- Filename: House Price India.csv  
- Description: The dataset contains information on residential houses in India, including the target variable 'Price'.  
- Features include:
  - number of bedrooms  
  - area (in sqft)  
  - location  
  - number of bathrooms  
  - furnishing status  

## Tools and Libraries

- Python  
- Jupyter Notebook  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  

## Project Structure

house-price-prediction  
- House Price India.csv  
- house_price_prediction.ipynb  
- README.md  
- requirements.txt  

## Models Compared

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor (Best based on lowest MSE)  
- K-Nearest Neighbors Regressor  
- XGBoost Regressor  

## Evaluation Metrics

- Mean Squared Error (MSE)  
- R² Score  

## Results

The **Random Forest Regressor** gave the best performance with the **lowest Mean Squared Error (MSE)** and the highest R² Score among all models.

### Performance Table:

| Model              | MSE         | R² Score |
|--------------------|-------------|----------|
| Linear Regression  | 3.50e+10    | 0.751    |
| Decision Tree      | 1.15e+10    | 0.918    |
| KNN                | 2.55e+10    | 0.819    |
| XGBoost            | 1.03e+10    | 0.927    |
| **Random Forest**  | 6.11e+09    | 0.956    |

## Final Output

A scatter plot was generated comparing actual vs predicted prices using the **Random Forest** model. The predictions closely followed the actual values, showing high accuracy.

## How to Run

1. Clone this repository  
2. Ensure `House Price India.csv` is in the same folder as the notebook  
3. Open `house_price_prediction.ipynb` in Jupyter Notebook or Google Colab  
4. Run all cells in order  

## Author

Talasila Navya Annapurna  

GitHub: https://github.com/NavyaTalasila5  

LinkedIn: https://www.linkedin.com/in/navya-talasila-3134a1325/
