# COVID-19 Impact Analysis: Synthetic Interventions on Mobility Restrictions

## 📋 Overview

In this project I will analyze the relationship between mobility restrictions and COVID-19 fatalities using advanced statistical methods. Through **Synthetic Interventions** approach, we can estimate counterfactual scenarios to determine how different levels of mobility restrictions might have impacted mortality rates, with a special focus on Brazil.

The project demonstrates that countries implementing moderate mobility restrictions (like Brazil) could have significantly reduced COVID-19 deaths by adopting more severe mobility intervention measures.

## 🔍 Key Features

- **Rigorous Comparative Analysis** of different mobility restriction levels (Low, Moderate, Severe)
- **Counterfactual Estimation** using the Synthetic Interventions methodology
- **Focus on Brazil** as a case study for moderate restriction impact
- **Comprehensive Data Visualization** of mortality patterns across restriction categories
- **Evidence-based Insights** on public health intervention effectiveness

## 📊 Data Sources

The analysis leverages two primary datasets:
- **Johns Hopkins COVID-19 Database**: Provides comprehensive time-series data on COVID-19 deaths globally
- **Google Mobility Reports**: Quantifies mobility changes during the pandemic across different countries

## 🧪 Methodology

### Data Preparation
1. **Data Collection & Integration** - Mortality data from Johns Hopkins and mobility metrics from Google
2. **Preprocessing & Cleaning** - Handling missing values, outliers, and date normalization
3. **Feature Engineering** - Calculating daily metrics and creating mobility restriction categories

### Analysis Approach
1. **Clustering Countries** by mobility restriction levels based on Google mobility data
2. **Synthetic Intervention Modeling** to create counterfactual scenarios
3. **Time-Series Analysis** comparing actual vs. counterfactual outcomes
4. **Statistical Validation** to ensure robustness of conclusions

### Mathematical Foundation
The Synthetic Interventions method leverages matrix completion techniques to predict counterfactual scenarios, allowing estimation of what would have happened in Brazil if stricter mobility restrictions had been implemented.

## 📈 Key Findings

1. **Significant Mortality Reduction Potential** - Countries with severe mobility restrictions experienced substantially fewer COVID-19 deaths per capita
2. **Brazilian Counterfactual** - Modeling suggests Brazil could have prevented a significant number of deaths by implementing stricter mobility measures
3. **Intervention Timing Matters** - Early implementation of severe restrictions shows better outcomes than delayed responses

## 💻 Technical Implementation

- **Programming Language**: Python 3.10
- **Core Libraries**:
  - **pandas & numpy**: Data manipulation and numerical operations
  - **matplotlib, seaborn & plotly**: Data visualization
  - **scikit-learn**: Machine learning modeling

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/covid.git
cd covid

# Install dependencies
pip install -r requirements.txt

# Open the Jupyter notebook
jupyter notebook "Synthetic Interventions - Covid19.ipynb"
```

## 📁 Project Structure

```
covid/
├── Synthetic Interventions - Covid19.ipynb  # Main analysis notebook
├── data_global_data.csv                    # COVID-19 mortality dataset
├── data_global_mobility_report.csv         # Google mobility dataset
├── boxplot_continentes.html                # Interactive visualization
├── img/                                    # Visualizations and figures
│   ├── boxplots.png
│   ├── newplot.png
│   └── ...
├── README.md                               # Project documentation
└── LICENSE                                 # MIT License
```

## 📚 Further Research Opportunities

- Extending the analysis to other countries and regions
- Incorporating additional variables like vaccination rates and healthcare capacity
- Developing predictive models for future pandemic response planning
- Analyzing economic impact correlations with mobility restriction levels

## 🔓 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 References

- Abadie, A., Diamond, A., & Hainmueller, J. (2010). Synthetic Control Methods for Comparative Case Studies.
- Johns Hopkins University Center for Systems Science and Engineering. (2020). COVID-19 Data Repository.
- Google LLC. (2020). Google COVID-19 Community Mobility Reports.


