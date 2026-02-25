
---

# 2️⃣ Customer-Data-Quality-Audit

```markdown
# Customer Data Quality Audit

## Business Context
Poor data quality leads to inaccurate reporting, flawed analysis, and incorrect business decisions — especially in finance and customer analytics environments.

## Problem Statement
Conduct a comprehensive data quality assessment on a customer dataset to evaluate reliability, completeness, and consistency.

## Dataset Overview
- Customer demographic data
- Account activity data
- Financial indicators
- Unique identifiers

## Tools Used
- SQL Server
- Python (Pandas)
- Excel (validation checks)

## Data Quality Checks Performed
- Missing value analysis
- Duplicate record detection
- Outlier identification
- Invalid format detection (emails, IDs)
- Data type validation
- Referential integrity checks

## Key Findings
- Missing values in income and tenure fields impacted risk segmentation.
- Duplicate customer IDs created reporting inconsistencies.
- Extreme outliers skewed average revenue metrics.
- Inconsistent formatting in categorical fields affected grouping accuracy.

## Business Impact
- Incorrect churn prediction
- Misclassification of financial risk
- Inaccurate KPI reporting

## Recommendations
- Implement database constraints.
- Introduce validation rules during data entry.
- Schedule automated data quality monitoring.
- Standardize categorical value formats.

## Project Structure
sql/ – Data validation queries
python/ – Data profiling scripts
reports/ – Summary findings
README.md
