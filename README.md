# ChemBook Data Transforming 

This ReadMe documentation provides additional context and explains the process and outputs of the Python code snippets. While the original intention was to transform the data to resemble TraCCC and team 3 data, the final output follows similar formatting rules. 

## Process Overview 

### Data Preparation: 

- The code reads data from a CSV file named “ChemBook_final.csv” using the pandas library. 

- It groups unique CAS numbers by company name. 

- It groups product names, telephone numbers, emails, websites, and source URLs by company name. 

### Merging Dataframes: 

- The unique values from different columns are merged into one dataframe (cb_f). 

- The dataframes for CAS, product names, telephone numbers, emails, websites, and source URLs are merged into cb_f. 

### Data Transformation: 

- The script processes the data to create a consistent format. 

For example, it joins all Tel and Email values into one key-value pair called “Contact”. 

### Sorting and Indexing: 

The dataframe cb_f is sorted by ‘Company_ID’ and ‘Attribute_ID’ in ascending order. 

The index of cb_f is reset. 

## CSV Output Files: 

The processed data is saved to two CSV files:  

“ChemBook_final_t3.csv”: Contains information related to company names, CAS numbers, and other attributes. 

“ChemBook_final_traccc.csv”: Contains same details in the format of TraCCC data 

### Outputs 

#### ChemBook_final_traccc.csv: 

This file contains the following columns:  

- Company_ID: Unique identifier for each company. 

- Attribute_ID: Unique identifier for each attribute (e.g., Name, Contact, Source URL). 

- Attribute: Descriptive label for the attribute. 

- Value: Values associated with the attribute (e.g., company names, contact information). 

- The data is organized by company and attribute to look and work like TraCCC data. 

#### ChemBook_final_t3.csv: 

- Contains processed and transformed data for further analysis. 

## Usage 

Ensure you have the required Python libraries installed (e.g., pandas). 

Run the provided Python script to process your chemical company data. 

Review the generated CSV files for insights and further analysis. 