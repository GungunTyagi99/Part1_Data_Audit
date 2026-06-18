
# Data Quality Report

## Datasets Audited

- customers
- orders
- support_tickets
- web_events_snapshot
- churn_labels
- intervention_history

## Checks Performed

### Missing Values
Checked all datasets for missing values.

### Duplicate Records
Verified duplicate customer and order records.

### Outliers
Reviewed extreme values in:
- monetary_180d
- recency_days
- sessions_30d

### Invalid Values
Checked ratings, discounts and ticket counts.

## Recommendations

- Monitor missing support ticket fields.
- Validate extreme monetary values.
- Standardize categorical values.
