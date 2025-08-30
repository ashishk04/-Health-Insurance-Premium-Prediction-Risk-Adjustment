# -Health-Insurance-Premium-Prediction-Risk-Adjustment
This project builds a machine learning-based insurance pricing model that predicts healthcare charges for individuals and evaluates premium-setting strategies to improve insurer profitability. It combines statistical modeling, advanced ML techniques, and financial simulations to demonstrate how data-driven methods can optimize insurance pricing.

Tools & Libraries Used

Python (core language)

Libraries: NumPy, Pandas (data handling), Matplotlib (visualization), Scikit-learn (ML models & pipelines), XGBoost (advanced regression), and KMeans (customer segmentation).

Power BI for visualization of per-policy performance and profitability trends.

📊 Project Workflow

Data Preprocessing: Cleaned and transformed health insurance dataset (age, sex, BMI, children, smoker, region, charges). Encoded categorical variables using OneHotEncoder and scaled numerical features.

Model Development:

Baseline: Linear Regression.

Advanced Models: Decision Tree, Random Forest, and XGBoost Regressor (best performer with R² ≈ 0.90).

Compared models using MAE, RMSE, and R².

Feature Importance: Identified smoking status (83%), BMI (9.9%), and age (4.4%) as the most influential drivers of insurance charges.

Simulation & Financial Metrics:

Applied a 15% load factor to predicted charges to simulate premium setting.

Modeled a +10% residual shrinkage scenario to test profitability under reduced error.

Calculated premiums, claims, profits, and loss ratios across scenarios.

Segmentation with KMeans: Clustered policyholders into low, medium, and high-risk groups for targeted pricing strategies.

Power BI Dashboard: Exported per-policy tables (predictions, premiums, profits) and built interactive charts for insurer decision-making.

✅ Key Outcomes

XGBoost reduced RMSE by ~26.6% compared to linear regression.

Simulated improvements showed higher premium accuracy and lower loss ratios.

Recommended insurers apply a 15% premium uplift for high-risk groups (e.g., smokers, high BMI) for sustainable, risk-aligned pricing.
