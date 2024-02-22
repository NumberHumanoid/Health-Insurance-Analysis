# Health-Insurance-Linear-Regression-Analysis

![Banner-Health-Insurance](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/55e0eb1f-e608-4e6c-9525-e0825680ad06)

# Background Context
- (US Health Insurance Data set): This data set contains 1338 rows of insured data, where the Insurance charges are given against the following attributes of the insured:
  - Age: age of primary beneficiary
  - Sex: insurance contractor gender, female, male
  - BMI: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
  - Number of Children: Number of children covered by health insurance / Number of dependents
  - Smoker: Smoking
  - Region: the beneficiary’s residential area in the US, northeast, southeast, southwest, northwest
  - Charges: Individual medical costs billed by health insurance
 
### Objective: 
- Leverage statistical modeling techniques, specifically linear & polynomial regression, to analyze and predict individual medical costs billed by health insurance based on a variety of factors listed above. Through this analysis, the project aims to uncover the underlying patterns and relationships between these factors and insurance charges, thereby providing insights into how different attributes contribute to the determination of insurance premiums.

### ✨ [Full Data Analysis Here](https://rpubs.com/numberhumanoid/1147343) ✨

## Data Source
- [Data Source](Assets/insurance.csv)

# Business Insights
## **Correlation with Charges:**
![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/36c2ac83-4163-4514-aa1d-be80113767fe)

  - **Smoking** has the highest positive correlation with insurance charges. This suggests that smoking status should be a primary factor in risk assessment and premium calculation.
  - **Age** also shows a significant positive correlation with charges, indicating that older individuals tend to incur higher medical costs.

## Demographic Insights:
![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/8941ad34-7ff4-4094-b3dc-23fe27652b2d)
  - The distribution of charges between smokers and non-smokers indicates that smokers, on average, are charged significantly more for insurance. This insight reinforces the importance of smoking cessation programs and their potential to lower insurance costs.

![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/d9eefac6-8c24-4be4-8531-381de93aaf2e)
  - The age and charges relationship graph indicates that charges increase with age, which may inform age-related premium adjustments.

## Geographical Insights:
![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/dfe70993-147d-446f-bdd6-14e597dc1373)
  - There is a slight variation in total charges by region, which may reflect the cost of living, access to healthcare facilities, or regional health trends. This might inform regional sales strategies and resource allocation.

## Distribution of BMI:
![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/5753689a-814f-4ea5-b834-eff6da058197)
  - The distribution of BMI among the insured individuals is slightly right-skewed, which could indicate a higher risk of obesity-related health issues. This may necessitate tailored health programs to address this risk.
![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/aede822b-54a9-460d-8339-a2d9c307d66d)
  - However this was mitigated upon analysis, due to statistical modeling. Perhaps further analysis could be done for more granular analysis.

## Gender Distribution:
![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/edc7c540-b13e-4666-b48b-1ebe3f216465)
- The gender distribution is balanced, indicating that the data set provides a fair representation across genders. However, the analysis did not show a significant difference in charges between males and females.

## Predictive Model Performance:
![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/169e4f30-3b06-4b4f-aa3b-afa6db9577db)
  - The linear regression model provides a reasonable level of accuracy, but the presence of outliers and high residuals for some predictions indicates that a more complex model, such as polynomial regression, might capture the nuances of the data better.


![image](https://github.com/NumberHumanoid/Health-Insurance-Analysis/assets/149428916/f4e9425b-c4c9-4294-b43b-e8e2d49087ed)
  - The polynomial regression model shows a noticeable improvement in R-squared value, suggesting that it captures the relationship between variables and charges more effectively than a simple linear model.

















