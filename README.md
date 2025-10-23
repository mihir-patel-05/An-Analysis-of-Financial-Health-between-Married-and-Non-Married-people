# An Analysis of Financial Health between Married and Non-Married People

**Authors:** Mihir Patel, Arnav Patel, Allisandra McKague, Siva Sai Ruthwik Suravarapu, Elif Yazgan  
**Date:** April 30, 2025  
**Language:** R (RMarkdown)  
**Files Included:**  
- `Final_Writeup_project.Rmd` – R Markdown source code for analysis  
- `Final_Writeup_project.pdf` – Final compiled report with all results and visuals  

---

## Overview
This project explores whether **marital status influences financial well-being** by analyzing a simulated dataset from the **ISLR “Credit” dataset**.  
We examine variables such as **income, credit score, balance, credit limit, and debt-to-income ratio** between married and non-married individuals to uncover potential trends in financial stability.

Our goal:  
> “Does marital status significantly affect an individual's financial health?”

---

## Research Questions
We address the following five sub-questions:

1. **Income vs Credit Score:**  
   How does income compare between married and non-married people?

2. **Variance in Credit Card Usage:**  
   Does the variance in credit card balance and cards differ across age groups?

3. **Credit Score Significance:**  
   Is there a statistically significant difference in average credit scores?

4. **Credit Limit Comparison:**  
   Do married people have higher credit limits?

5. **Debt-to-Income Ratio:**  
   Does the DTI ratio differ significantly by marital status?

---

## Methodology
- **Dataset:** ISLR’s `Credit` dataset (~400 observations, 12 variables)  
- **Segmentation:** Split into married and non-married groups  
- **Techniques Used:**
  - Data wrangling (`dplyr`, `tidyverse`)
  - Linear regression (`geom_smooth`)
  - Hypothesis testing (t-tests, p-value computation)
  - Visualization (`ggplot2` for scatterplots, boxplots, violin plots)
  - Variance and null distribution analysis

---

## Key Findings
- No statistically significant difference in **credit scores** or **credit limits** between groups.  
- **Non-married individuals** showed higher variance in balance, indicating slightly less financial stability.  
- **Debt-to-Income ratios** were nearly identical for both groups (p-value ≈ 0.98).  
- Overall, **no strong evidence** supports that marital status causes better financial health, despite weak correlations.

---

## Limitations
- Dataset was **simulated**, not real population data — limits generalization.  
- Small sample size reduced the power of hypothesis testing.  
- Future work should use **real-world credit data** and incorporate **age-based regression analysis** for stronger results.

---

## Future Directions
- Use authentic demographic and financial datasets for improved reliability.  
- Conduct **correlation matrix analysis** across all financial indicators.  
- Expand the scope to include **education level, employment, and geographic factors**.

---

## File Descriptions

| File | Description |
|------|--------------|
| `Final_Writeup_project.Rmd` | R Markdown source code with all data wrangling, plots, and statistical tests |
| `Final_Writeup_project.pdf` | Final rendered report including all figures, analyses, and references |

---

## References
- [Experian: Married Consumers Have Higher Credit Scores and Debt (2020)](https://www.experian.com/blogs/news/2020/02/married-consumers-credit-score-debt/)
- [Pew Research Center: Wealth Gaps Between Married and Single Americans (2022)](https://www.pewresearch.org/)
- [JPMorgan Chase: Understanding Your Credit Card Limit](https://www.chase.com/personal/credit-cards/education/credit-score/credit-card-limit)
- [Federal Reserve Bank of St. Louis: Marriage and Wealth (2020)](https://www.stlouisfed.org/publications/in-the-balance/2020/marriage-and-wealth)

---
