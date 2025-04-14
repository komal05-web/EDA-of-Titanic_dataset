# Titanic Dataset Analysis

## Overview
This project explores the Titanic dataset to uncover patterns, relationships, and factors influencing passenger survival. The analysis covers data cleaning, visualization, feature engineering, and initial insights.

## Key Steps
1. **Data Cleaning**:
   - Missing `Age` values filled with the median.
   - Missing `Embarked` values removed.
   - Missing `Cabin` values replaced with "Unknown".

2. **Feature Engineering**:
   - New feature `FamilySize` created from `SibSp` and `Parch`.

3. **Visualizations**:
   - **Histograms**: Age distribution to understand passenger demographics.
   - **Boxplots**: Fare distribution across passenger classes.
   - **Scatterplots**: Relationship between Age and Fare with survival overlay.
   - **Pairplot**: Correlations among numerical features.
   - **Heatmap**: Correlation matrix showcasing feature relationships.

4. **Key Observations**:
   - First-class passengers paid higher fares and had better survival rates.
   - Age shows diverse demographic groups onboard.
   - Family size highlights family group travel dynamics.

## Tools & Libraries
- **Python**: Data processing and visualization.
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib.

## Conclusion
The project identifies survival-related trends based on demographics, class, and fare. The findings provide a foundation for predictive modeling and further exploration.
