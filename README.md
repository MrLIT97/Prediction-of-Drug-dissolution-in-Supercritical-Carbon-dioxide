# Prediction-of-Drug-dissolution-in-Supercritical-Carbon-dioxide

**Introduction:**
This project contributes to solving the medical challenges faced with poor aqueous solubility of drugs for the purpose of Active Pharmaceutical Ingredient (API) extraction and administration. It is specifically a predictive modeling optimization project  on drug dissolution in supercritical carbon dioxide (SCCO2). SCCO2 has been found to be the most commonly used supercritical fluid for various applications across scientific research and developments, most especially in Nano-technology. 

This project focuses on its application to drug formulation and extraction processes during pharmaceutical production. Estimating the solubility of a drug in SCCO2 helps to guide the formulation of the drug for improved drug delivery, especially for anticancer drugs. 

**Dataset Description:**
The dataset consists of experimental measured solubility of drugs over a diversified range of therapeutic classes. It was collected over a range of verifiable publication journals.

drug - name of drug
temp - operating temperature (K)
press - operating pressure (bar)
mw_drug - molecular weight of drug (g/mole)
mp_drug - melting point of drug (K)
rho_scco2 - density of scco2 (kg/m3)
sol - equilibrium solubility (g/L)
sol_mol_frac - equilibrium solubility in mole fraction

**Expertise Demonstrated:**
1. Research Study
2. Data Collection
3. Data Cleaning and Wrangling
4. Exploration Data Analysis
5. Data manipulation
6. Machine Learning modeling and Optimization

**Packages used:**
- Excel 
- Python 

**Machine Learning methods:**
1. Robust scaling on feature variables to colapse wide range
2. Quantile Transformation on target variable to normalized skewness 
3. model building
4. Optimization approach:
   - gridsearch under the hood
   - model performance visualization to track error minimization
5. Model comparison

**Models Selected:**
- Ensemble Models
  * Decision Trees
  * Random Forest
  * Gradient Boosting
- K-Nearest Neighbour
- Support Vector Machine
- Artificial Neural Network

**Result:**
Ensemble Models perform the best with Gradient Boosting taking the lead. This is own to their robust learning method.
  




