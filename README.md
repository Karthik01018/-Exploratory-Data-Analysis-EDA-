# -Exploratory-Data-Analysis-EDA-

## 1. Summary Statistics

We calculated basic summary statistics for the numerical features of the dataset, which include:
- **Mean**: Average value for each feature.
- **Median**: The middle value in the dataset.
- **Standard Deviation (std)**: Measures the spread of the data.
- **Min/Max**: The minimum and maximum values for each feature.

These statistics provide a quick overview of the central tendency, spread, and any potential outliers in the data.

## 2. Histograms and Boxplots for Numeric Features

We visualized the distribution of numerical features, including `Age` and `Fare`, using the following:
- **Histograms**: Show the frequency distribution of numeric features. We also included Kernel Density Estimation (KDE) to visualize the data's smooth probability distribution.
- **Boxplots**: Display the spread of the data, highlighting the median, quartiles, and any potential outliers.

These plots helped us identify if the data is skewed or normally distributed and if there are any extreme outliers in the dataset.

## 3. Pairplot/Correlation Matrix for Feature Relationships

We examined the relationships between features using:
- **Pairplot**: Plots pairwise relationships between numeric features like `Age`, `Fare`, `Pclass`, and `Survived`. This visualization helps us spot potential correlations between variables and understand their interactions.
- **Correlation Matrix**: Shows the pairwise correlation between numerical features. This helps identify which features are strongly correlated, which could be useful for feature engineering and model selection.

## 4. Identifying Patterns, Trends, or Anomalies

Through the visualizations and statistical analysis, we identified:
- **Patterns**: Relationships between variables such as the correlation between `Fare` and `Pclass`, or `Age` and `Survived`.
- **Trends**: We observed the distribution of fares and ages, identifying trends like younger passengers having a higher chance of survival.
- **Anomalies**: Outliers in the `Age` and `Fare` distributions were detected, which could indicate data entry errors or extreme values that may need to be treated during data preprocessing.

## 5. Feature-Level Inferences from Visuals

From the generated visuals, we inferred:
- **Age**: The age distribution appears somewhat skewed, with most passengers being younger adults. Outliers in `Age` may need to be addressed.
- **Fare**: The fare distribution is highly skewed, with a few passengers paying much higher fares than the majority.
- **Pclass**: The class distribution provides insight into the social/economic strata of passengers, which could influence survival rates.
- **Sex and Embarked**: The distribution of `Sex` (more male passengers) and `Embarked` (different embarkation ports) was analyzed using count plots.

## Conclusion

This analysis provides a comprehensive overview of the dataset's features. The visualizations and summary statistics highlight the distribution and relationships between variables. Identifying outliers, trends, and correlations is essential for further data preprocessing and modeling. These insights can inform the next steps in predictive modeling or further analysis.
