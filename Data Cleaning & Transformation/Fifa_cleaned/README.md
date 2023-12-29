
The FIFA dataset encompasses comprehensive player attributes in the realm of professional football. This curated collection, refined for clarity and accuracy, includes information on player profiles, club affiliations, contract statuses, and performance metrics. With meticulous data cleaning, it lays a strong foundation for in-depth analysis and insights.

**Summary:** 
Here's a summary of the cleaning process performed on the FIFA dataset:

Duplication Handling:
Eliminated duplicate entries, ensuring data integrity.

Column Refinement:
Streamlined columns by removing "Name" and enhancing readability with a rename of "LongName" to "Name."
Trimmed excess information by discarding "photoUrl," "playerUrl," and "Loan Date End" columns.

Null Values Management:
Mitigated potential discrepancies by addressing and filling null values with 0 or empty strings 

Data Polish:
Optimized the "Club" column by removing extraneous characters.
Enhanced clarity by omitting stars ("★") from "W/F," "SM," and "IR" columns.

Height and Weight Refinement:
Transformed "Height" to centimeters and "Weight" to kilograms for consistency.
Provided more descriptive column names: "Height in cm" and "Weight in kg."

Contract Status Simplification:
Simplified the "Contract" column into insightful categories like "ON LOAN," "CONTRACT OVER," "NOT ON CONTRACT," and "ONGOING."

Date Management:
Dissected "Joined" into individual columns for month, date, and year, fostering better temporal analysis.

Currency Conversion:
Enhanced usability by converting "Value," "Release Clause," and "Wage" columns to numeric values.
