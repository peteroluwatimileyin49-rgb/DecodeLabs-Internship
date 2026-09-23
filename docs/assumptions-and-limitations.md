# Assumptions and Limitations

## Assumptions

- The provided dataset is assumed to represent the complete sample supplied for the internship exercise.
- `OrderID` is treated as the unique identifier for an order.
- Dates are interpreted using the standardized date values in the cleaned workbook.
- Missing `CouponCode` values are treated according to the handling documented in the Project 1 report.
- High-value records identified through the IQR method are treated as potential outliers, not automatic errors.

## Limitations

- The dataset is an internship sample and may not represent the wider e-commerce market.
- The analysis is based on the available fields and time period, covering 2023–2025.
- Outlier detection identifies unusual values but does not explain why those values occurred.
- Spreadsheet-based analysis is less reproducible than a version-controlled code pipeline unless the workbook formulas and steps are preserved.
- The repository contains multiple similarly named workbook versions. A single canonical final workbook should be selected before formal submission.

## Recommended final checks

- Select one workbook as the official cleaned dataset and rename it clearly.
- Confirm that all report figures match the official workbook.
- Complete the data dictionary with every column in the final workbook.
- Record any manual decisions made during cleaning.
- Verify that screenshots and reports use the same dataset version.
