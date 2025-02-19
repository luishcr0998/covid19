# Synthetic Interventions on COVID-19 Fatalities

This project analyzes the impact of mobility restrictions on COVID-19 fatalities, with a special focus on Brazil. Using advanced statistical methods and machine learning algorithms, we simulate various intervention scenarios to understand their potential effects on reducing virus-related deaths.

## 🎯 Objectives
- Develop a robust model to simulate the impact of different levels of mobility restrictions
- Analyze the effectiveness of mobility restrictions in reducing COVID-19 fatalities
- Compare different restriction levels (Low, Moderate, Severe)
- Estimate counterfactuals based on severe restrictions
- Visualize and understand how different intervention levels might have affected mortality rates

## 📊 Data Sources
- **Johns Hopkins COVID-19 Database**: Mortality data
  - Provides information on cumulative COVID-19 related deaths
  - Pre-processed data to show daily values
- **Google Mobility Reports**: Restriction level data
  - Information on mobility patterns during the pandemic

## 🔬 Methodology
1. **Data Collection**
   - Extraction from Johns Hopkins database
   - Integration with Google mobility reports

2. **Data Preprocessing**
   - Data cleaning and validation
   - Missing value treatment
   - Date conversion and formatting
   - Daily metrics calculation

3. **Model Development**
   - Implementation of Synthetic Interventions method
   - Model calibration and validation
   - Robustness analysis

4. **Scenario Analysis**
   - Simulation of different restriction levels
   - Scenario comparison
   - Counterfactual evaluation

5. **Results Interpretation**
   - Statistical analysis of results
   - Data visualization
   - Conclusions and recommendations development

## 🛠️ Tools and Technologies
- **Python**: Main programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib & Seaborn**: Data visualization
- **Plotly Express**: Interactive visualizations
- **Scikit-learn**: Machine learning algorithms

## 📝 How to Use
1. **Environment Setup**
   ```bash
   git clone [REPOSITORY_URL]
   cd covid
   pip install -r requirements.txt
   ```

2. **Running the Analysis**
   - Open the Jupyter Notebook `Synthetic Interventions - Covid19.ipynb`
   - Execute cells in sequential order
   - Results and visualizations will be generated automatically

## 📈 Project Structure
```
covid/
├── data/                      # Raw and processed data
├── notebooks/                 # Jupyter notebooks
│   └── Synthetic Interventions - Covid19.ipynb
├── README.md                 # This file
└── requirements.txt          # Project dependencies
```

## 🔍 Key Results
- Comparative analysis of different restriction levels
- Counterfactual estimates for alternative scenarios
- Interactive result visualizations
- Insights on restriction measures effectiveness

## 📚 References
- Johns Hopkins COVID-19 Database
- Google Mobility Reports
- Scientific literature on synthetic interventions in epidemiology

## 👥 Contributions
Contributions are welcome! Please read the contribution guidelines before submitting pull requests.

## 📄 License
This project is under the MIT License. See the `LICENSE` file for more details.


