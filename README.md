# Students Performance — Data Visualization

A visual exploration of the Students Performance dataset (1,000 students, 8 attributes), covering meaningful questions to ask before visualizing, data structure checks, chart-based analysis of scores and demographics, and a summary of findings.

## Project Structure

```
.
├── StudentsPerformance.csv                        # Source dataset (1,000 × 8)
├── Student_Performance_Data_Visualization.ipynb   # Jupyter notebook with the full visualization workflow
└── README.md
```

## Dataset Description

| Column | Type | Description |
|---|---|---|
| gender | Categorical | Student gender (male / female) |
| race/ethnicity | Categorical | Five anonymised groups (group A – group E) |
| parental level of education | Categorical | Highest parental qualification |
| lunch | Categorical | standard or free/reduced (proxy for socio-economic status) |
| test preparation course | Categorical | completed or none |
| math score | Numeric | Score on a 0–100 scale |
| reading score | Numeric | Score on a 0–100 scale |
| writing score | Numeric | Score on a 0–100 scale |

## Visualization Workflow

1. Define meaningful questions before visualizing
2. Check data structure (shape, dtypes, summary statistics)
3. Build univariate visuals — distribution of scores (histogram), gender split (pie chart)
4. Build comparative visuals — average scores by subject (bar chart)
5. Build relationship visuals — math vs. reading (scatter plot), spread and outliers (box plots)
6. Build correlation visuals — inter-subject correlation (heatmap)
7. Summarize findings

## Questions Explored

1. **Subject comparison** — Which subject do students score highest/lowest in, on average?
2. **Gender** — What does the gender split look like?
3. **Score distribution** — What does the spread of math scores look like — normal, skewed, outliers?
4. **Inter-subject relationship** — Are math and reading scores related to each other?
5. **Spread across subjects** — How do math, reading, and writing compare in terms of spread and outliers?
6. **Correlation** — How strongly are the three subjects correlated with each other?

## Visualizations Included

| Chart | Purpose |
|---|---|
| Bar chart | Average score comparison across subjects |
| Pie chart | Gender distribution |
| Histogram | Math score distribution |
| Scatter plot | Math vs. reading score relationship |
| Box plots | Spread and outliers across math, reading, and writing scores |
| Heatmap | Correlation between the three subjects |

## Summary of Findings

- The dataset contains 1,000 student records.
- Reading scores have the highest average among the three subjects; math scores are comparatively lower.
- The gender distribution is nearly balanced, with slightly more female students.
- All three subjects are strongly, positively correlated — reading and writing are the most closely linked.
- Visualization makes it easier to identify trends and compare student performance at a glance.

## Requirements

pandas, matplotlib, seaborn

## Getting Started

Open the notebook:
```
jupyter notebook Student_Performance_Data_Visualization.ipynb
```
Execute cells top-to-bottom to reproduce the visualizations.

## Author

Sampada G S

## License

This is a self-study analysis for demonstration purposes only. Dataset structure follows the classic Kaggle "Students Performance" dataset.
