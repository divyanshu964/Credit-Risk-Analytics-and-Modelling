# Credit-Risk-Analytics-and-Modelling
This project helps banks identify high-risk borrowers, reduce loan defaults, optimize approval rules, and balance risk vs profitability using data-driven insights on income, employment, credit history, loan behavior and prective modelling (ML).

The Credit Risk Analytics project analyzes borrower data to identify patterns that drive loan defaults and to help design better underwriting, risk management, and profitability strategies. Using a Kaggle dataset, it evaluates multiple borrower and loan attributes such as age, income, employment, home ownership, loan intent, loan grade, interest rate, and credit history.

1. A key finding is that age significantly impacts default risk, with younger borrowers showing a higher tendency to default. This suggests that age-based segmentation can improve underwriting decisions. Income also plays a crucial role, but raw counts can be misleading. While many defaulters fall in the mid-income range (30k–100k), percentage analysis reveals that very low-income groups (<10k and <20k) have extremely high default rates, often exceeding 80%. As income increases, default rates decline sharply, making higher-income borrowers relatively safer.

2. Home ownership is another strong predictor of risk. Renters have the highest default rates, while homeowners and those with mortgages are significantly more reliable. This indicates that stability and asset ownership reduce credit risk.

3. The relationship between employment length and default risk is less clear, but borrowers with less than two years of employment or missing employment data show higher default rates. This supports the idea of enforcing a minimum employment duration for loan approval.

4. From a loan characteristics perspective, certain loan purposes such as debt consolidation and medical expenses have higher default rates, while education, personal, and venture loans perform better. Additionally, the loan grading system is effective, as lower grades (E, F, G) show significantly higher default rates compared to higher grades (A, B). However, large loan amounts within mid-tier grades (like B) contribute disproportionately to risk, indicating a need for tighter control.

5. The analysis also shows that higher loan amounts and higher interest rates are associated with increased default risk. Similarly, borrowers with a higher loan-to-income ratio (loan_percent_income) are much more likely to default. This is one of the strongest predictors, with default rates rising steeply as repayment burden increases.

6. Interestingly, credit history length does not show a clear inverse relationship with default risk, contradicting common assumptions. Even borrowers with long credit histories may default, suggesting that other factors like income and loan burden are more influential.

7. Another critical insight is that borrowers with prior defaults are significantly more likely to default again, with nearly double the default rate compared to others. This makes past default behavior a key factor in risk assessment.

8. From a profitability standpoint, the bank appears to price risk appropriately, as higher-risk customers are generally charged higher interest rates. However, the optimal balance between risk and return lies in the 10–15% interest rate range, particularly around 11–12%, where profits are maximized without excessive defaults.


Overall, the project identifies clear high-risk and low-risk borrower profiles. High-risk borrowers are typically young, low-income individuals with high loan burdens and large loan amounts. In contrast, safer borrowers have higher incomes, stable employment, low loan-to-income ratios, home ownership, and good credit grades.


The final recommendation is to implement stricter underwriting rules based on income thresholds, employment stability, loan burden limits, prior default history, and home ownership status. These measures can significantly reduce default rates while maintaining profitability.
