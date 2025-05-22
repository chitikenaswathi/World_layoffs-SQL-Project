# World_layoffs-SQL-Project
Here I have cleaned the layoff data by removing duplicates, standardizing the data and removing any rows and columns that are not required.
## Project Overview:
"This project focuses on cleaning and preparing layoff data for analysis."
## Data Cleaning
In the Data Cleaning part, we will be focussing on 4 things.

1. Remove Duplicates
2. Standardize the data
3. Handle Null values or blank values
4. Remove Rows and Columns if necessary or if they are for no use
## Checking the raw data
![Screenshot (7)](https://github.com/user-attachments/assets/154141ec-45ad-4a6a-8d70-424edcf7b22e)
## Creating a duplicate table to work and protect the raw data
![Screenshot (8)](https://github.com/user-attachments/assets/ae030b7e-59ee-4e0e-815a-0d6b20776e59)
## Creating another table to manipulate data and create extra columns
/creating a new table named layoffs_worksheet2 by copying clipboard>create statement and add one extra column named row_num/
![Screenshot (9)](https://github.com/user-attachments/assets/b2203306-bd79-4360-a6a5-8bea8724287e)
## Inserting values to this new table and adding an extra column
/* inserting values into this new table and assigning row_num by creating a partition on each column so that each unique row is assigned as 1 and if there are any duplicates then it will be assigned as 2 in the row_num */
![Screenshot (10)](https://github.com/user-attachments/assets/6c1511ec-eb4e-465e-9205-956ecb6e08d1)
## 1. Removing the duplicates
#### Checking the duplicates
![Screenshot (11)](https://github.com/user-attachments/assets/22d0fd26-76b6-47f3-a83d-3ac8769860d5)
#### Deleting the duplicates
![Screenshot (12)](https://github.com/user-attachments/assets/5b3b6580-cc81-474d-8be9-03078ea456d2)











