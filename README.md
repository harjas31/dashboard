# Clothing Brand Sales Dashboard

This project involves creating an interactive Excel dashboard for a clothing brand, based on raw sales data. The dashboard provides insightful visualizations and is equipped with slicers for enhanced interactivity.

## Visualization
![Dashboard](https://github.com/harjas31/dashboard/blob/main/annual_report.png)

## Data Transformation

### Raw Data
The initial dataset included the following columns:
- index
- Order ID
- Cust ID
- Gender
- Age
- Date
- Status
- Channel
- SKU
- Category
- Size
- Qty
- Currency
- Amount
- Ship City
- Ship State
- Ship Postal Code
- Ship Country
- B2B

### Processed Data
The final dataset used for the dashboard included the following columns:
- index
- Order ID
- Cust ID
- Gender
- Age
- Group
- Date
- Month
- Status
- Channel
- SKU
- Category
- Size
- Qty
- Currency
- Amount
- Ship City
- Ship State
- Ship Postal Code
- Ship Country
- B2B

### Data Cleaning and Transformation
1. **Age Grouping**: The `Age` column was categorized into three groups:
   - Teenager (below 30)
   - Adult (30-50)
   - Senior (above 50)
2. **Gender Standardization**: The `Gender` column values were changed from 'M' and 'W' to 'Men' and 'Women'.
3. **Quantity Normalization**: Ensured consistent formatting in the `Qty` column by converting numeric representations to their respective words.

## Dashboard Creation
Using the processed data, I created an interactive Excel dashboard utilizing pivot tables and slicers. The dashboard includes various visualizations such as:
- Orders vs Sales over the months
- Sales distribution across top states
- Gender and age group analysis
- Order channels distribution
- Order status breakdown
- Sales comparison between men and women

The slicers allow for dynamic filtering of data based on different channels, categories, and months, providing an interactive experience for the users.


