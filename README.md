St. Louis Real Estate Statistical Analysis
A statistical analysis of 28 home sale prices in the St. Louis area, completed as a final project for MATH 1320 Intro to Probability & Statistics at the University of Missouri.

Overview
This project analyzes St. Louis residential real estate data from 2023–2025 to answer key questions about home pricing, architectural style, garage presence, neighborhood differences, and square footage as a price predictor.

Analyses Conducted
Descriptive Statistics — mean, median, standard deviation, IQR, five-number summary
One-Sample Z-Test — tested a housing blog's claim that the average sale price is $300,000
Two-Sample Welch T-Test — compared sale prices between ranch and colonial style homes
One-Proportion Z-Test — tested whether more than 75% of homes have a garage
Chi-Square Test — tested independence between architectural style and garage presence
ANOVA — compared average sale prices across three neighborhoods (CWE, Bevo, Soulard)
Linear Regression — used square footage to predict sale price (R² = 0.9834)

Key Findings
Average sale price is likely around $300,000 (95% CI: $280,398 – $310,030)
No significant price difference between ranch and colonial style homes
CWE is the most expensive neighborhood, Soulard the least
Square footage is a strong predictor of sale price — each additional sq ft adds ~$220.50

Tools Used
R 4.5.3
Quarto (.qmd)
Posit Cloud (RStudio)

Files
final-project.qmd — Quarto source file with all R code and analysis
final-project.pdf — Rendered final report
