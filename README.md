# Python Basics & Data Cleaning with Pandas

## Brief Project Summary
* **Objective**: Learned Python basics and performed data exploration and cleaning using Pandas on a dataset containing jacket product logs (`jackets.csv`).
* **Data Exploration**: Explored a dataset containing 29 rows and 24 attributes, identifying the key financial attribute `initial_price`.
* **Missing Values**: Addressed the `discount` column containing null values by applying localized imputation to fully preserve the rest of the observational rows.
* **Basic Operations**: Extracted a structural slice featuring `title`, `category`, and `initial_price`, then filtered transactions where pricing exceeded 2,000.
* **Feature Engineering**: Introduced a randomized vector column `Quantity` (ranging from 1 to 3 units per item) and performed broadcast math to generate a brand new derived variable: `total_amount = initial_price * Quantity`
* **File Export**: The final refined dataset was outputted as a standalone file named `cleaned_jackets_dataset.csv`.
