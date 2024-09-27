# ETL-Pipeline #

Greetings,

Welcome to the ETL-Pipeline repository! This project utilizes Python, Pandas and regular expressions to extract and transform crowdfunding data into relational table CSV files for creation/hydration of a PostgreSQL database.

**Repository Structure:**

- "ETL_Mini_Project_ABayemi_MRamsey.ipynb": Executed jupyter notebook file containing data cleaning, DataFrame creation and subsequent CSV file exports for SQL database hydration
  
- "crowdfunding_db_schema.sql" - SQL schema creation code for generation of the SQL database structure (Tables, Columns, Datatypes, etc.). Generated via "https://www.quickdatabasediagrams.com/"
  
- "crowdfunding_db_schema_picture.png" - A visualization of the entity relationship diagram utilized for SQL schema creation code. Generated via "https://www.quickdatabasediagrams.com/"
  
- "SQL_Table_Select_Statements.sql" - SQL code for individual table data output. Select * statements to verify proper table creation, data type declaration & correct data hydration/import
  
- 'SQL_Output_Pictures' - Directory containing pictures for each table's 'SELECT *' statement PostgreSQL output for verification. Included are four picutres corresponding to the "Campaign", "Category", "Contacts" and "Subcategory" tables ("Campaign_SQL_Table_Output.png", "Category_SQL_Table_Output.png", "Contacts_SQL_Table_Output.png", "Subcategory_SQL_Table_Output.png")
  
- 'Resources' - Directory containing the two initial starting datasets ("crowdfunding.xlsx" & "contacts.xlsx"), as well as the four generated CSV files ("campaign.csv", "category.csv", "contacts.csv", "subcategory.csv")

**Team Members:**

Adrian Bayemi & Makonnen Ramsey

Cheers!
