# Student Habits vs Academic Performance

## Datasets Overview
This synthetic dataset explores how various lifestyle habits influence academic performance in students. It includes 1,000 fictional student records and over 15 features spanning:
- Daily study hours

- Nightly sleep duration and quality

- Social media and screen time

- Diet quality

- Mental health ratings
  
- Final exam scores

- ...

*Sources:* https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance

## 2. Exploration Data Analysis (EDA)
1. Distributions
- Visualize the distribution of:
- Study hours
- Sleep duration per night
- Daily social media usage
=> This helps identify central tendencies and potential outliers.

2. Correlation with Exam Score
Quantify how strongly each of the following correlates with final exam score:

Study hours

Sleep quality

Diet score

Screen time, etc.

Use Pearson or Spearman correlation.

3. Sleep vs. Exam Performance
Compare average exam scores between:

Students sleeping < 6 hours

Students sleeping > 8 hours

Identify how sleep quantity impacts outcomes.

4. Correlation Heatmap
Create a heatmap of pairwise correlations across all variables. Look for:

Hidden relationships

Feature clusters

Redundant predictors

5. Diminishing Returns on Study Time
Group students by study-hour bins (e.g., 0–2 hrs, 2–4 hrs, etc.) and:

Plot average exam score for each bin

Include error bars (standard deviation or confidence intervals)

Analyze where additional studying ceases to provide big gains

6. Mental Health Segmentation
Segment students by mental health rating (e.g., Low / Medium / High) and:

Compare distributions of sleep, diet, and screen time across groups

Explore patterns in lifestyle behavior and well-being

## 3. Predictive Modeling
Train a Linear Regression model to predict final exam scores based on lifestyle features.

Key steps:

Train/test split

Feature scaling (if needed)

Model evaluation using metrics like R² and MAE/MSE

Analyze feature coefficients to interpret influence

Consider experimenting with regularization (e.g., Ridge, Lasso) or tree-based models for improved robustness and insights. 
