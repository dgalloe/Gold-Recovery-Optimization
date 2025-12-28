# Gold-Recovery-Optimization
Developed a machine learning prototype for Zyfra, a company specializing in heavy industry efficiency solutions. The model predicts the amount of gold recovered from raw ore based on extraction and purification data, aiming to optimize production and eliminate unprofitable parameters.

## 1. Objectives 🎯
- Develop a model to predict gold recovery efficiency during purification processes
- Optimize production parameters to maximize mineral recovery yield
- Analyze and prepare industrial data for machine learning applications
- Evaluate model performance using the sMAPE metric for both rougher and final stages
- Compare custom model performance against baseline dummy models

## 2. Key Findings 🏆
- Successfully built and optimized regression models for gold recovery prediction
- Achieved superior performance over baseline models in both recovery stages
- Identified key process parameters influencing recovery efficiency
- Demonstrated the practical application of machine learning in mineral processing
- Established a robust methodology for industrial process optimization
 
## 3. Visualizations Included 🎨
- Data distribution plots for key recovery metrics
- Feature importance analysis charts
- Model performance comparison visualizations
- Recovery efficiency trend analysis
- Error distribution plots for model evaluation

## 4. Skills Demonstrated 🛠️
- Data Processing: Handling industrial datasets with multiple measurement points
- Machine Learning: Implementing and tuning regression models (Linear, Random Forest)
- Feature Engineering: Preparing and selecting relevant process parameters
- Model Evaluation: Using sMAPE and cross-validation techniques
- Statistical Analysis: Applying hypothesis testing and correlation analysis
- Data Visualization: Creating informative plots for process analysis

## 5. Technical Details 💻
- Programming Language: Python
- Main Libraries: pandas, scikit-learn, matplotlib, seaborn, numpy
- Models Used:
  - Linear Regression
  - Random Forest Regressor
  - Dummy Regressor (baseline)
- Data: Industrial gold recovery process data with 87 features and 16,860 entries
- Key Metrics: sMAPE (symmetric Mean Absolute Percentage Error)
- Validation: Cross-validation and train-test splits

## 6. Installation and Usage
```bash
# Clone the repository
git clone https://github.com/yourusername/gold-recovery-optimization.git

# Navigate to project directory
cd gold-recovery-optimization

# Install required dependencies
pip install -r requirements.txt

# Run the analysis notebook
jupyter notebook Second_project.ipynb
