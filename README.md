# Teen Mental Health Analysis

This project explores the relationship between teenagers' digital habits, lifestyle, and mental health using Python. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, data visualization, correlation analysis, and statistical testing to identify patterns in the dataset.

The goal of this project is to understand how factors such as social media usage, sleep, age, and gender relate to anxiety, stress, and overall mental health risk.

---

## Project Objectives

- Explore patterns in teen mental health data
- Analyze the relationship between social media usage and anxiety
- Study how sleep habits relate to stress levels
- Compare mental health indicators across age, gender, and social media platforms
- Validate findings using statistical tests

---

## Dataset Overview

The dataset contains approximately **1,000+ records** of teenagers aged **13–19 years**.

### Features Included

- Age
- Gender
- Daily social media usage
- Platform usage
- Sleep hours
- Screen time before sleep
- Academic performance
- Physical activity
- Social interaction level
- Stress level
- Anxiety level
- Addiction level
- Depression label
- Mental health risk score
- Sleep quality
- Digital wellbeing flag

---

## Project Workflow

### 1. Data Loading

- Loaded the dataset using Pandas
- Examined the dataset using:
  - `head()`
  - `info()`
  - `describe()`

---

### 2. Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records

---

### 3. Exploratory Data Analysis

The following analyses were performed:

- Distribution of age and gender
- Distribution of platform usage
- Sleep quality analysis
- Digital wellbeing analysis
- High-stress users
- Poor-sleep users
- Average anxiety level by:
  - Platform
  - Age
  - Gender
- Average mental health risk score by age and gender
- Stress level comparison across different platforms
- Top 10 highest mental health risk cases

---

### 4. Feature Engineering

Three additional features were created:

- **Sleep Deficit**
  - Calculated as `8 - sleep_hours`

- **Heavy User**
  - Users spending more than 5 hours per day on social media

- **Risk Category**
  - High Risk
  - Low/Medium Risk

---

### 5. Correlation Analysis

A correlation matrix was created to study relationships between numerical variables such as:

- Social media usage
- Sleep hours
- Stress level
- Anxiety level
- Mental health risk score

A heatmap was also created to visualize these relationships.

---

### 6. Statistical Analysis

Three statistical tests were performed to support the analysis.

#### Independent t-test

Compared anxiety levels between TikTok users and users of other platforms.

**Purpose:**
Determine whether the average anxiety levels differ significantly between the two groups.

---

#### Pearson Correlation Test

Examined the relationship between:

- Sleep hours
- Stress level

**Purpose:**
Measure the strength and direction of the linear relationship between sleep and stress.

---

#### Chi-Square Test

Tested the association between:

- Platform usage
- Mental health risk category

**Purpose:**
Determine whether platform usage and risk category are statistically associated.

---

## Visualizations

The project includes the following visualizations:

- Bar chart of anxiety level by platform
- Bar chart of anxiety level by gender
- Bar chart of anxiety level by age
- Scatter plot of daily social media usage vs anxiety level
- Correlation heatmap

---

## Key Findings

- Anxiety levels differ across social media platforms.
- Sleep duration is significantly related to stress levels.
- Platform usage is associated with mental health risk categories.
- Heavy social media users tend to have higher anxiety and stress levels.
- Mental health risk varies across different age and gender groups.

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## Limitations

- The dataset appears to be synthetic or created for educational purposes.
- Depression labels are highly imbalanced.
- Several variables are self-reported and may contain subjective bias.
- The dataset represents a single point in time and cannot be used to determine cause-and-effect relationships.

---

## Conclusion

This project demonstrates a complete exploratory data analysis workflow using Python. It combines data cleaning, visualization, feature engineering, and statistical testing to better understand patterns in teen mental health data.

The findings suggest that digital behavior and lifestyle factors, particularly social media usage and sleep habits, are associated with mental health indicators such as anxiety, stress, and overall risk. These results can serve as a starting point for future work, including predictive modeling and machine learning.
