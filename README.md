# Machine-Learning-Association-Rule-Analysis
This project focuses on performing Association Rule Analysis using vaccine data. The goal is to compare the results obtained from two popular algorithms, Apriori and FP-Growth, and examine the association rules using the confidence metric.

## Dataset
The analysis is conducted using a dataset obtained from the CDS (Centers for Disease Control and Prevention) spanning the years 1990 to 2022. The dataset consists of multiple CSV files, amounting to a total size of approximately 2.5GB. However, due to size limitations, the complete dataset cannot be uploaded to the repository. Instead, a trimmed version of the dataset is provided for reference.

## Algorithms
1. **Apriori:** This algorithm is used to discover frequent itemsets in the dataset and generate association rules based on support and confidence thresholds.
2. **FP-Growth:** This algorithm employs a tree-based approach to efficiently mine frequent itemsets and derive association rules.

## Analysis and Results
The Association Rule function is applied to the dataset, utilizing the confidence metric. The focus of the analysis is to examine the association between the vaccine administration and the age groups.

From the analysis, it is observed that the majority of the younger age group received the Pfizer vaccine. This finding aligns with the fact that Pfizer was the first vaccine approved for the younger age group.
