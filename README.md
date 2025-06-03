# Drugs side effects analysis (By using Python – Jupyter Notebook)
This project focuses on analyzing drug reviews to understand user satisfaction, drug effectiveness, side effects, and overall scores. The dataset includes various features such as medical condition, user age, benefits, side effects, and ratings. The analysis was conducted using Python in a Jupyter Notebook environment. Both regression and classification models were applied to predict and classify overall drug scores, along with statistical tests and data visualizations to uncover trends, patterns, and key medical insights.

## Dataset used
Dataset = ""

## Objectives of the project
1) Perform exploratory data analysis (EDA) on drug review data
2) Identify trends in medical conditions, drug effectiveness, side effects, and user satisfaction
3) Apply regression and classification models to predict and classify overall drug scores
4) Visualize key insights using Python and libraries like Matplotlib and Seaborn
   
## Questions solved
1) Which medical condition has the highest number of unique drugs available?
2) What is the average overall user score by medical condition?
3) Which medical conditions receive the highest and lowest user ratings?
4) Which drugs have the highest and lowest number of user reviews?
5) What are the most commonly reported side effects by users?
6) Is there a correlation between the number of reviews and user ratings?
7) How do average ratings vary by prescription type (Rx, OTC, both)?
8) What are the most commonly used generic and brand-name drugs?
9) Which are the top 10 most common drug classes in the dataset?
10) Which medical conditions have the most drugs considered low or high risk in pregnancy?
11) Which drugs have alcohol use restrictions, and what conditions do they treat?
12) Is there a correlation between drug activity percentage and user rating?
13) Do prescription drugs (Rx) have significantly higher overall scores than non-Rx drugs?
14) Do higher pregnancy risk drugs tend to have higher user ratings?
15) How accurately can machine learning models predict or classify drug overall scores?


## Libraries Used
The following Python libraries were used during the data cleaning, exploration, visualization, and analysis phases:
1) NumPy – for efficient numerical computations
2) Pandas – for data manipulation, cleaning, and analysis
3) Matplotlib – for creating basic visualizations and plots
4) Seaborn – for advanced statistical and exploratory visualizations
5) Scikit-learn (sklearn) – for building and evaluating machine learning models
6) WordCloud – for visualizing the most frequent words in drug names or conditions

   
## Python file (Jupyter Notebook)
Python File = ""

## PowerPoint presentation
PPT = ""

## PDF file of PowerPoint presentation
pdf = ""

## Final Observations & Storyline
1) Acne leads in drug diversity with 39 unique drugs (7.98%), followed by Hypertension and Pain, indicating broader treatment options for these conditions. User satisfaction is highest for Erectile Dysfunction drugs (avg. score: 17.90), while Cancer (2.54) and Stroke (3.01) rank lowest, showing disparities in perceived effectiveness.
2) Drugs like Bisacodyl (1,357 reviews) show strong user engagement, while Neomycin, with only one review, indicates limited usage. Despite assumptions, no significant correlation exists between review count and rating (R² = 0.002), while common side effects such as lip/tongue irritation and stomach pain suggest critical safety concerns.
3) Drugs available both as prescription and OTC options receive the highest average ratings (6.97), slightly outperforming Rx-only and OTC-only categories. Top generic drugs like Isotretinoin and Metformin reflect focus areas like acne and diabetes, while brands like Bronkaid dominate respiratory care. Diabetes drugs dominate low-risk pregnancy categories, while Hypertension and Pain top high-risk lists.
4) Alcohol restrictions are most common in drugs for Diabetes and Pain (34% combined), demanding patient caution. Interestingly, high-risk pregnancy drugs are rated more favorably (8.87 vs. 7.44; p = 0.0027), and prescription drugs significantly outperform non-prescription ones in overall scores (8.89 vs. 6.38; p = 0.000), showing a trade-off between efficacy and safety.
5) Modeling confirmed this complexity: Random Forest Regressor had the strongest predictive power (R² = 0.369, RMSE = 1.132), outperforming all other regression models. For classification, Random Forest again led (accuracy: 71.28%, F1: 0.497), with XGBoost and Gradient Boosting close behind. However, class imbalance remained a challenge, especially in lower rating categories.


