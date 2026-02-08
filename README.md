# Logistic Regression for Heart Disease Prediction
This project developed a logistic regression model to predict heart disease using a medical dataset (303 patients, 14 variables). Feature selection was performed using stepwise regression with AIC, resulting in a final model with 10 predictors. Model diagnostics included VIF (low multicollinearity), likelihood ratio tests, Wald tests, ROC analysis (AUC > 0.9), and confusion matrix evaluation. A classification threshold of 0.6 was chosen empirically to balance predictions and outcomes.

# Conclusions
The model achieved satisfactory performance (86% accuracy).

Some intuitive predictors (age, cholesterol) were excluded, indicating weak statistical contribution in this dataset.

The optimal decision threshold was higher than 0.5, suggesting the model tended to be overly sensitive.

Both false positives and false negatives carried useful clinical interpretation.

Wider confidence intervals indicate that a larger dataset could improve model stability and precision.

# Customer Segmentation Using Clustering Methods
This project applied hierarchical clustering (Ward.D2), K-means, and PAM to segment customer data (2000 records, 8 features). Euclidean distance matrices and dendrograms were used to identify cluster structures. Clustering quality was evaluated using wb.ratio, Pearson gamma, Dunn index, and ANOVA to assess variable importance. Comparisons were made between solutions with different numbers of clusters and across clustering methods.

# Conclusions

Hierarchical clustering and K-means produced similar segmentation structures, while PAM differed more significantly.

A 4-cluster hierarchical solution offered better internal–external distance ratios and more balanced cluster sizes, while 3 clusters showed better Dunn index separation.

Cluster profiles enabled meaningful consumer segmentation (e.g., affluent married individuals vs. less wealthy female groups).

# Multiple Correspondence Analysis of Food Preferences
This project used Multiple Correspondence Analysis (MCA) to explore relationships among categorical variables describing food preferences (274 observations, 4 qualitative variables). A Burt matrix was used for analysis, and factor maps visualized relationships between categories. The first two dimensions explained about 47.9% of total variance. Clustering tendencies were examined using factor space distributions and density isolines.

# Conclusions
Two main behavioral patterns emerged: traditional cuisine with fresh juice and low dessert preference vs. western cuisine with carbonated drinks and desserts.

Nationality strongly biased results due to sample imbalance, making it beneficial to exclude this variable in later analyses.

Food type and drink preference were the strongest drivers of variation.

Only moderate-quality clusters were identified due to overlapping category structures and limited representation of some groups.
