# Walmart Case Study: Central Limit Theorem and Hypothesis Testing

This project involves analyzing a Walmart dataset to understand purchasing patterns among different customer demographics. The analysis includes data preprocessing, exploratory data analysis (EDA), and hypothesis testing using the Central Limit Theorem (CLT) to draw meaningful conclusions and provide actionable recommendations for Walmart.

## Project Overview

The primary goals of this project are:

1. **Exploratory Data Analysis (EDA)**:
   - Examine the dataset structure, characteristics, and summary statistics.
   - Detect and handle missing values and outliers.
   - Analyze the distribution of purchase amounts using visualizations and descriptive statistics.

2. **Hypothesis Testing and Confidence Intervals**:
   - Calculate the average purchase amounts for female and male customers.
   - Compute confidence intervals for the average purchase amounts using sample data.
   - Analyze the effects of different confidence levels on the intervals.
   - Compare purchasing patterns based on marital status and age groups.

## Project Steps

### 1. Importing and Analyzing the Dataset

- Load the dataset.
- Display the first few rows and dataset info to understand its structure.

### 2. Detecting Null Values and Outliers

- Check for null values and handle them if any.
- Calculate descriptive statistics and create boxplots to detect outliers.

### 3. Data Exploration

- Filter the dataset by gender.
- Calculate the average purchase amount for female and male customers.
- Compute the 95% confidence interval for the average purchase amount of female customers.

### 4. Central Limit Theorem and Confidence Intervals

- Calculate confidence intervals for different confidence levels (90%, 95%, 99%) for both female and male customers.

### 5. Conclusions

- Compare the confidence intervals for male and female customers.
- Determine if the intervals overlap and conclude if there is a statistically significant difference between their average spending.

### 6. Marital Status and Age Group Analysis

- Analyze the average purchase amounts for married and unmarried customers.
- Group data by age and calculate the mean purchase amount for different age bins.
- Compute confidence intervals for each age group.

### 7. Recommendations and Action Items

Based on the analysis, here are some recommendations for Walmart:

- **Personalized Marketing**: Tailor marketing campaigns to different demographics, such as gender and marital status.
- **Product Placement**: Optimize product placement based on purchasing patterns of different customer segments.
- **Loyalty Programs**: Develop loyalty programs targeting specific customer groups to increase engagement and spending.
- **Customer Experience**: Enhance the shopping experience to cater to the unique needs of different customer segments.
- **Data Analysis**: Continuously analyze customer data to identify trends and preferences.
- **Inclusive Promotions**: Run promotions that appeal to diverse customer groups.
- **Feedback and Engagement**: Encourage customer feedback to improve the shopping experience.

By implementing these strategies, Walmart can better cater to the needs of its customers, potentially increasing customer satisfaction and sales.

## Repository Structure

- `WalmartCaseStudyCLT.ipynb`: Jupyter notebook containing the complete code for the analysis and hypothesis testing.
- `walmart_data.csv`: Dataset used for the analysis.

## Usage

To run the analysis, follow these steps:

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3. Open the Jupyter notebook:
    ```bash
    jupyter notebook WalmartCaseStudyCLT.ipynb
    ```
4. Run the cells in the notebook to execute the analysis.

---
Aman Sinha - sinha.amansinha@gmail.com