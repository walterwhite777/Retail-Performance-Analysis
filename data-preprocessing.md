# Data Preprocessing: Cleaning and Preparation

## Objective
To ensure the dataset is suitable for analysis, I performed cleaning and preprocessing steps to enhance data quality, focusing on revenue growth and customer retention metrics. This process aligns with best practices for delivering reliable insights to senior management.

## Steps
1. **Remove Invalid Records**:
   - **Quantity < 1**: Removed records with negative or zero quantities, as these do not contribute to revenue growth and may indicate returns or errors.
   - **UnitPrice < 0**: Excluded records with negative unit prices, as these are invalid for revenue calculations.

2. **Create Revenue Column**:
   - Added a new column, `Revenue`, calculated as `UnitPrice * Quantity`. This metric is critical for analyzing revenue growth trends and customer performance.

## Example Code (Python)
Below is the Python code used for preprocessing:

## Outcome
The cleaned dataset ensures accurate analysis of revenue growth, customer retention, and market expansion, providing a solid foundation for the insights delivered to the CEO and CMO.