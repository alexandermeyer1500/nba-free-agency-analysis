# NBA Free Agency Analysis

## Overview
This project analyzes whether NBA free agency spending impacts team performance and improvement. Using team spending and win percentage data, I explored whether higher spending is associated with better results.

## Question
Does NBA free agency spending impact team performance?

## Motivation
Free agency spending is often viewed as a way for NBA teams to improve performance, but its actual impact is uncertain.

## Method
I collected data on free agency spending and win percentages for the top 10 NBA teams by spending following the 2024–2025 season. I created a performance improvement metric by comparing each team’s win percentage before and after free agency. I then used correlation and linear regression to analyze the relationship between spending and both team performance and improvement.

## Results
- Spending vs performance: weak negative correlation (r ≈ -0.23)
- Spending vs improvement: moderate negative correlation (r ≈ -0.35)
- Outlier analysis identified San Antonio and Detroit as overperformers, while Sacramento and Memphis significantly underperformed expectations.

## Key Findings
- Free agency spending showed a weak negative relationship with team performance.
- Spending showed a moderate negative relationship with improvement in win percentage.
- Higher spending did not guarantee better results.
- San Antonio and Detroit outperformed expectations.
- Sacramento and Memphis underperformed expectations.

## Conclusion
Free agency spending alone is not a reliable predictor of NBA team performance or improvement. While some teams significantly outperform or underperform expectations, the results suggest that team success depends on factors beyond financial investment, such as roster construction, player development, injuries, and team chemistry.

## Limitations
This analysis uses a small sample size and only considers a limited number of teams and seasons. Future analysis could include player efficiency metrics, roster continuity, injury data, and multiple seasons.

## Tools Used
- Python
- pandas
- NumPy
- matplotlib
- Google Colab
