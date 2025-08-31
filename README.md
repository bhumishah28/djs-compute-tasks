# djs-compute-tasks
# Compute Task 2: Data Pre-processing & Visualization

## Dataset
- UFC Fighters dataset
- 4111 rows × 18 columns (after cleaning: 4111 × 16 usable features)

## Steps Done
1. Loaded dataset with Pandas
2. Checked shape, datatypes, missing values
3. Cleaned data (filled NaN, dropped duplicates, ensured numeric types)
4. Visualized dataset:
   - Distribution of height & weight
   - Fighter stance counts
   - Scatterplot: Height vs Reach
   - Scatterplot: Wins vs Losses
   - Boxplot: Wins by stance
   - Correlation heatmap

## Key Insights
- **Height & Reach:** Strong positive correlation — taller fighters usually have longer reach.
- **Stances:** Orthodox stance is most common among fighters.
- **Win/Loss Distribution:** Most fighters cluster around balanced records, with few extreme outliers.
- **Correlations:** Some striking/takedown stats are strongly related, which could be useful for predictions.

## Conclusion
The dataset is cleaned and ready for advanced analysis.  
EDA revealed clear patterns in physical attributes, stances, and performance stats.
