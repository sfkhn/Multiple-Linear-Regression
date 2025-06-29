\# 📊 Multiple Linear Regression: Predicting CO₂ Emissions



This project uses \*\*Multiple Linear Regression\*\* to predict \*\*CO₂ emissions (g/km)\*\* from features like:



\- Engine size

\- Fuel consumption (MPG)



It was built as part of the Coursera \*\*AI Engineer Professional Certificate\*\* course.



---



\## 📁 What's Inside



\- `Mutiple\_linear\_regression.ipynb`: Jupyter notebook with code and explanation

\- Visualizations of feature relationships

\- 3D regression plane showing model predictions

\- Model coefficients and intercept analysis



---



\## 🎯 Goal



Build a machine learning model that can predict CO₂ emissions for cars using real-world vehicle data.



---



\## 📌 Steps Covered



1\. Load and explore the dataset

2\. Check correlations between features and the target

3\. Drop redundant or collinear features

4\. Standardize features using `StandardScaler`

5\. Fit a multiple linear regression model

6\. Visualize the predictions and regression plane in 3D

7\. Interpret coefficients and intercepts in original scale



---



\## 📈 Example Output



Model equation:

CO₂ = 329.13 + 17.86 × EngineSize - 5.02 × FuelConsumption\_MPG




This means:

\- Higher engine size increases CO₂ emissions

\- Higher MPG reduces emissions (as expected)



---



\## 📚 Requirements



You can install dependencies using pip:

```bash

pip install numpy pandas matplotlib scikit-learn



