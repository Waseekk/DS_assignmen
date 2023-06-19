# DS_assignment

1.The assignment was done in Google Colab the version of Python used was python 3.9
2.The libraries needed to be installed are pandas, matplotlib, seaborn, numpy and sklearn 
3. The code shall run smoothly if all the libraries are installed so running the colab from the top shall suffice. Also the excel file must downloaded in the computer for the reading it.


For Assignment 1.

1.	Download the Excel file: Download the attached Excel file from the repository. The file contains two sheets: Sheet1 and Sheet2.
2.	Create a Pivot Table: Using the data from Sheet1, a pivot table was created with specific information structure:
•	The pivot table shows the sum of income as the value.
•	Columns include the values of Gender and MaritalStatus.
•	Rows are arranged in the following order: Division, Customer Name, ID.
3.	Matching IDs: In Sheet2, additional IDs are provided. To match the IDs between Sheet2 and Sheet1, a new column named "Matched" was added to Sheet1. A formula was used to compare the IDs and display the result as True or False.



For Assignment 2.


1.	Separated the data from Sheet 1 in the Excel file and saved it in a new Excel sheet.
2.	Converted the Excel file to a CSV file by saving it from Excel as a CSV format.
3.	Loaded the CSV file into your Python environment, likely using the Pandas library.
4.	Removed the "ID" column from the loaded data frame.
5.	Encoded the data to have similar values, which likely involved standardizing or normalizing the data to make it more comparable.
6.	(Bonus Task) Applied K-means clustering based on divisions within the data. This involved grouping the data points into clusters based on their similarities.
7.	Downloaded the modified file, likely in CSV format, without omitting the output. This file should include the transformed data without the "ID" column.
