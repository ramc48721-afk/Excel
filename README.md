# Student Health & Social Media Analytics Dashboard

## 1. Project Overview

The **Student Health & Social Media Analytics Dashboard** explores relationships between students' social media usage, AI tool usage, sleep patterns, physical activity, and mental and physical health indicators.

The project transforms student-related data into visual insights through an interactive dashboard. It helps identify digital usage patterns, compare health indicators across demographic groups, and investigate how digital habits may be associated with student well-being.

## 2. Project Objectives

- Analyze daily social media usage and AI tool usage among students.
- Explore relationships between screen time, sleep duration, physical activity, and health scores.
- Compare digital habits and health indicators across age groups, gender, and education levels.
- Identify patterns in students' mental and physical health.
- Present findings through an interactive, easy-to-understand dashboard.
- Provide data-informed recommendations that encourage healthier digital habits.

## 3. Dataset Information

The dashboard analyzes student-related data covering digital habits, lifestyle patterns, demographic characteristics, and health indicators.

### Dashboard summary

- **Total records:** 16,000
- **Students in the current dashboard view:** 5,027
- **Education level selected:** University
- **Gender:** All
- **Age group:** All
- **Sleeping mode:** All

The figures above reflect the dashboard screenshot. The number of students in the current view may differ from the total number of records because filters are applied.

### Key data attributes

| Category | Attributes |
|---|---|
| Demographics | Age group, gender, education level |
| Digital habits | Daily social media hours, AI tool usage hours |
| Lifestyle | Sleep duration, physical activity |
| Mental well-being | Mental health score |
| Physical well-being | Physical health score |
| Derived analysis | Health status, correlations, group comparisons |

> Add the original dataset source, license, and full column schema here. Do not publish private student information or sensitive raw health data.

## 4. Dashboard Features

### Interactive filters
Users can filter the dashboard by:
- Education level
- Gender
- Age group
- Sleeping mode

### KPI cards
The current dashboard view reports the following average values:

| KPI | Displayed value |
|---|---:|
| Students in view | 5,027 |
| Average social media usage | 4.56 hours/day |
| Average AI tool usage | 2.62 hours/day |
| Average sleep duration | 6.52 hours/night |
| Average mental health score | 72.5 / 100 |
| Average physical health score | 88.0 / 100 |

### Age group analysis
Compares average daily social media and AI tool usage across age groups to identify differences in digital behavior.

### Social media and AI usage by education
Compares average usage among high school, college, and university students.

### Comparison by gender
Compares social media usage, AI tool usage, sleep duration, and physical activity across gender groups.

### Health status distribution
Shows the proportions of students classified as Good, Average, or Bad according to the dashboard's health-status categories.

### Social media vs. mental health
Visualizes the relationship between social media usage and mental health scores.

### Health score comparison
Compares average mental and physical health scores across education levels.

### Daily activity time
Summarizes time spent on social media, AI tools, sleep, and physical activity.

### Correlation analysis
Displays correlations between selected digital habits, lifestyle variables, and health indicators.

### Data quality and recommendations
Summarizes record counts, missing values, completeness, outlier checks, key findings, conclusions, and suggested actions.

## 5. Key Insights

The following observations are based on the displayed dashboard and should be verified against the source dataset before formal reporting.

1. **Social media usage is substantial.** Students in the current view average 4.56 hours per day on social media, compared with 2.62 hours per day using AI tools.
2. **Sleep duration may warrant further investigation.** Average sleep is 6.52 hours per night. Further analysis can examine whether sleep duration varies alongside mental health scores.
3. **Social media and mental health show a negative association.** The dashboard reports a correlation of **r = -0.40**, indicating that higher social media usage tends to be associated with lower mental health scores in this dataset.
4. **Physical activity and mental health show a positive association.** The reported correlation is **r = 0.42**.
5. **Social media usage and physical activity show a negative association.** The reported correlation is **r = -0.31**.
6. **Sleep duration and mental health show a positive association.** The reported correlation is **r = 0.31**.
7. **Most students fall into the Good or Average health categories.** The chart displays approximately 63% Good, 37% Average, and a very small Bad category. Verify the exact counts and percentages against the source data.
8. **Health scores appear similar across education levels.** The displayed comparisons show relatively small differences between high school, college, and university groups.

**Important interpretation note:** Correlation does not establish causation. These results describe associations in the analyzed data and do not prove that one behavior causes a health outcome.

## 6. Data Quality Assessment

The dashboard's data quality section reports:

| Metric | Displayed result |
|---|---:|
| Total records | 16,000 |
| Missing values | 0 |
| Data completeness | 100.0% |
| Social media usage outliers (> 3 SD) | 0.12% |

These are the values shown in the dashboard. Confirm the calculations and the scope of each metric against the underlying dataset. Outliers should be investigated rather than automatically removed, as they may represent valid observations.

## 7. Recommendations

- **Promote balanced screen time:** Encourage students to monitor and manage their daily social media usage.
- **Support healthy sleep routines:** Encourage consistent sleep schedules and investigate the relationship between sleep and well-being.
- **Encourage physical activity:** Promote regular exercise, movement breaks, and reduced sedentary time.
- **Build digital well-being awareness:** Help students understand balanced and intentional technology use.
- **Explore lower health scores responsibly:** Investigate patterns in aggregate data while respecting privacy and avoiding unsupported individual-level conclusions.
- **Perform deeper statistical analysis:** Examine whether age, gender, education level, sleep, and physical activity jointly relate to the health indicators.
- **Validate findings:** Use suitable statistical tests, confidence intervals, and longitudinal data where available before making stronger claims.

These recommendations are intended to support student well-being, not to diagnose health conditions.

## 8. Tools and Technologies

The dashboard demonstrates analytical activities such as:

- Data cleaning and preparation
- Exploratory data analysis (EDA)
- Descriptive statistics
- Correlation analysis
- Outlier detection
- Data visualization
- Interactive filtering and KPI reporting

**Document only the tools actually used in this project.** Depending on your implementation, these might include Python, Pandas, NumPy, Matplotlib, Seaborn, Power BI, Tableau, or Excel. The dashboard screenshot alone does not confirm the technology stack.

## 9. Project Workflow

1. **Data collection:** Obtain the student lifestyle, digital usage, and health dataset.
2. **Data preprocessing:** Validate data types and check missing values, duplicates, and inconsistent records.
3. **Exploratory data analysis:** Review distributions, summary statistics, and variable relationships.
4. **Statistical analysis:** Calculate correlations and identify potential outliers.
5. **Dashboard development:** Build KPI cards, filters, comparison charts, and health-status visualizations.
6. **Insight generation:** Interpret observed patterns and identify questions for further investigation.
7. **Recommendations:** Translate findings into practical suggestions for digital well-being and healthy lifestyles.

## 10. Conclusion

The **Student Health & Social Media Analytics Dashboard** demonstrates how data analytics can be used to investigate relationships between students' digital habits and health indicators.

The dashboard brings together interactive visualizations, comparative analysis, correlation metrics, and data quality indicators. Its findings highlight associations between social media usage, sleep duration, physical activity, and mental health scores, while emphasizing the need for careful interpretation.

Overall, the project illustrates how raw data can be transformed into understandable insights that support further analysis and informed discussions about healthier digital habits among students.

## 11. Future Enhancements

- Add time-based analysis to track changes in student behavior.
- Explore validated predictive models with appropriate safeguards.
- Include additional lifestyle variables, such as diet, study hours, and academic workload, if available.
- Add statistical significance testing and confidence intervals.
- Enable deeper drill-down analysis across demographic groups.
- Develop privacy-conscious recommendations based on validated findings.

## 12. Suggested Repository Structure

Adapt this structure to the files included in your actual repository:

```text
student-health-social-media-analytics/
├── data/
│   └── README.md
├── notebooks/
│   └── exploratory_data_analysis.ipynb
├── dashboard/
│   └── dashboard_file
├── images/
│   └── dashboard.png
├── README.md
├── requirements.txt
└── .gitignore
```

Do not include private student information or sensitive raw health data. If the dataset is publicly available, document its source and license.

[image]()

## Project Tags

`Data Analytics` `Student Well-being` `Social Media Analytics` `Health Analytics` `Exploratory Data Analysis` `Correlation Analysis` `Data Visualization` `Dashboard` `Digital Well-being`
