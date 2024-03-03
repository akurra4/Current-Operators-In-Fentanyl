# Table of Contents 
1.	Introduction 
2.	Data Extraction 
3.	Combining Data 
4.	Saving to CSV 
5.	Contributing 
6.	Dataset 
 
## Introduction 
Chemical compounds play a crucial role in various scientific and industrial applications. This repository aims to centralize data related to different compounds, making it easier for researchers and enthusiasts to access and analyze relevant information. 
## Data Extraction 
The provided Python code extracts data from a specific website related to chemical compounds. Here’s how it works: 
- The code initializes a Chrome driver using Selenium and navigates to a target webpage. 
- It retrieves information about chemical companies, including dates, product names, prices, and weights. 
- The extracted data is then organized for further analysis. 
## Combining Data 
In addition to extracting data, the code snippet demonstrates how to combine information from multiple DataFrames. By appending one DataFrame to another and resetting the index, you can create a comprehensive dataset. 
## Saving to CSV 
Once you’ve collected and combined the data, you can save it to a CSV file. The provided code snippet shows how to specify the output path and export the DataFrame to a CSV format. 
