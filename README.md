# MSCS_634_Lab_6
Lab 6: Association Rule Mining with Apriori and FP-Growth
# MSCS_634_Lab_6: Association Rule Mining with Apriori and FP-Growth

## Purpose

This lab explores association rule mining techniques using the Apriori and FP-Growth algorithms on a transactional dataset. The goal is to identify frequent itemsets and generate meaningful association rules, providing insights into purchasing patterns. Visualization techniques with Seaborn help interpret these patterns effectively.

## Key Insights

- The Apriori algorithm was faster (0.0635 seconds) compared to FP-Growth (0.7187 seconds) on this dataset.
- Both algorithms identified consistent frequent itemsets, including popular items like *whole milk*, *other vegetables*, and *rolls/buns*.
- FP-Growth found additional itemsets beyond those discovered by Apriori.
- Visualization of item frequencies and association rules helped highlight strong relationships and support decision-making.

## Challenges and Resolutions

- Contrary to common expectations, FP-Growth ran slower than Apriori, likely due to dataset size and characteristics.
- Visualization clarity was maintained by limiting plots to the top 10 frequent itemsets.
- Support thresholds were carefully chosen to balance runtime and meaningful output.
- Data preprocessing with `TransactionEncoder` ensured smooth transformation of raw transactions into a format compatible with mining algorithms.

## Repository Contents

- `association_rule_mining_lab.ipynb`: Jupyter Notebook containing the full analysis and visualizations.
- `README.md`: This file summarizing the lab purpose, findings, and challenges.


