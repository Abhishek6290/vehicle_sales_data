# Vehicle Sales Data Cleaning Project

This project focuses on cleaning and preprocessing a vehicle sales dataset using **Python** and **pandas**, making it ready for analysis or machine learning workflows.



##  Dataset Overview

The dataset includes information about vehicle sales, production, inventory, suppliers, and customer satisfaction. It contains **800 rows** and **17 columns**, with data points such as:

- Vehicle ID, Model, Type  
- Sales & Production Dates  
- Sales Quantity, Price, Revenue  
- Inventory Levels  
- Supplier Info  
- Market Share, Profit Margin, Customer Ratings  



##  Data Cleaning Steps

The following operations were performed in **Google Colab** using `pandas`:

1. **Uploaded CSV File**  
   via Google Colab’s `files.upload()`.

2. **Renamed Column Headers**  
   Converted to lowercase and replaced spaces with underscores for consistency.

3. **Handled Missing Values**  
   Checked for nulls using `.isnull()` and decided whether to drop or fill them.

4. **Removed Duplicate Rows**  
   Used `.drop_duplicates()` to eliminate redundant entries.

5. **Standardized Text Columns**  
   Cleaned and standardized values in `vehicle_type`, `region`, and `supplier` using string functions.

6. **Converted Date Columns**  
   Used `pd.to_datetime()` to convert all date columns to a consistent `datetime` format (`dd-mm-yyyy`).

7. **Fixed Data Types**  
   Ensured all numeric and categorical fields had appropriate data types (`int`, `float`, `datetime`).

8. **Exported Cleaned Data**  
   Saved the cleaned dataset back to CSV and enabled download using `files.download()`.



##  Tools & Technologies

- Python 3  
- Google Colab  
- pandas  
- CSV File Handling  
- Data Cleaning & Preprocessing  


##  Getting Started

1. Open the project in Google Colab.
2. Upload the original `vehicle_sales_data.csv` file.
3. Run the cells to clean and transform the dataset.
4. Download the cleaned version for further analysis or visualization.


## Output

- `cleaned_vehicle_sales_data.csv`: Ready-to-use dataset with standardized formats and cleaned entries.



##  Author

**Abhishek Verma**  
Data Analyst & BCA Student  
https://www.linkedin.com/in/abhishek-verma-52603a313/ 



