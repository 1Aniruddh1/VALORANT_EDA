## VALORANT 2026 EDA - Insights

This project is about Exploratory Data Analysis (EDA) on professional VALORANT player statistics to identify performance trends, correlations, and gameplay patterns.

### Top Player Performance

* A small group of players consistently ranks highest across rating, ACS, and K/D ratio.
* These players have a strong influence on match outcomes.

### Metric Correlations

* Strong positive correlation between:

  * ACS and Rating
  * K/D Ratio and Rating
* ACS serves as a reliable indicator of overall performance.

  <img width="273" height="524" alt="image" src="https://github.com/user-attachments/assets/0dc61901-267e-4ef9-ab7a-08bca6f8739b" />


### Kills vs Deaths

* Higher kills contribute positively to player rating.
* Higher deaths negatively impact performance.
* Efficiency and survivability are important factors.

### First Kill Impact

* Players with high first kills mostly take on the 'Duelist' role.
* Early eliminations provide a big advantage in future rounds.

  <img width="899" height="313" alt="image" src="https://github.com/user-attachments/assets/b6f32526-5aee-459a-9041-e4678b5de8ce" />


### Team Performance

* Teams with consistently high player ratings perform better overall.
* Balanced team performance is more effective than reliance on a single player.

### Outliers

* Some players achieve high ratings without top ACS values.
* This is due to unquantifiable data such as strategy, utility usage, or clutch plays.

---

## Visualizations

* Correlation heatmaps to examine relationships between metrics
* Scatter plots to analyze trends such as ACS vs Rating
* Role-based analysis of first kills

  <img width="540" height="298" alt="image" src="https://github.com/user-attachments/assets/01963f00-45ca-4851-81d5-e2c686c249d7" />




## Data Preprocessing

* Converted percentage-based columns such as Headshot % and Clutch %
* Removed irrelevant or inconsistent entries
* Cleaned data to ensure accuracy in analysis



## Conclusion

* Consistency across players is a key factor in team success
* Early-round impact (first kills) plays an important role
* ACS and K/D ratio are strong indicators of performance

