## Dataset 
1. `ChemBook_final.csv`
This spreadsheet contains detailed information on various chemical products. Below is a breakdown of the columns and what type of information they contain: 
- ID: A unique identifier for each entry. 
- Name: The name of the chemical product or the source where the chemical data is listed. 
- Tel: The telephone number associated with the chemical or source. 
- Email: The email address associated with the chemical or source. 
- CAS: Chemical Abstracts Service (CAS) registry number, a unique identifier for every chemical. 
- Product N (Product Name): The name of the chemical product being sold. 
- Stock We (Stock Weight): The weight of the stock being sold (presumably in grams or other relevant units). 
- Price (in USD): The price of the stock in US dollars. 
- Last Update: The date when the information was updated. 
- Remarks: Additional notes or comments regarding the chemical product, often including purity percentage and URL for more details. 
- Source_URL: The url link to the page that the information was scraped from. 
 
 
2. `ChemBook_final_names.csv`  
This Sheet contains the unique names and id’s of the company names. 
- ID: An id for the company name in the format CB_Company_# 
- Company Name: The names of the companies. 
 
 
3. `ChemBook_final_CAS.csv` 
This Sheet contains all the unique CAS numbers and id’s.  
-	ID: An id for the company name in the format CB_CAS_# 
- CAS: The CAS numbers of the chemicals 
 
4. `ChemBook_final_emails.csv` 
This Sheet contains all the unique emails and id’s  
- ID: An id for the company name in the format CB_Email_# 
- Email: The Email ID 
 
5. `ChemBook_final_phone.csv` 
This Sheet contains the unique phone numbers in all formats and id’s. 
- ID: An id for the Phone number in the format CB_Phone_# 
- Phone: The phone numbers of the companies, some records might have more than one number.

6. `ChemBook_final_web.csv` 
This Sheet contains the unique phone numbers in all formats and id’s. 
- ID: An id for the Website in the format CB_Web_# 
- Phone: the url text for the website of the post. 

7. `ChemBook_final_manufacturer.csv` 
This Sheet contains 25 companies that are identified as manufacturers. The sheet contains data related to the products sold and the date the company has been verified if it is.
- Company_Name: The name of the manufacturer
- CAS: A list of the CAS numbers for the products sold by these companies
- Product_Name: The name of the product being sold by the manufacturer
- Verified_On: The date on which the company was verified as a Corp. by Chemical Book.
