# Employee-Performance-and-Salary-Dataset
The dataset includes 50 curated tasks that displays key data manipulation techniques using Pandas.
Tasks:
1. Load the dataset into a Pandas DataFrame and display the first 10 rows. 
2. What are the column names and their respective data types in the dataset? 
3. How many rows and columns are there in the dataset? 
4. Select the Name, Age, and Salary columns using df[]. 
5. Select the first 5 rows of the DataFrame using the iloc method. 
6. Select all rows where the Department is "Sales" using the loc method. 
7. Select rows where the Salary is greater than 8000 and Status is "Active". 
8. Extract the rows where the employee has been with the company for more than 5 years and has a 
Performance Score of at least 4. 
9. Select every alternate row from the DataFrame using slicing with iloc. 
10. Retrieve rows where the employee belongs to "Sales" and has a Salary in the top 10% of all salaries. 
11. Replace all "Inactive" values in the Status column with "Retired". 
12. Add a new column Bonus where values are 10% of the Salary column. 
13. Update the Performance Score of employees in the "IT" department to 5 if it is NaN. 
14. Modify the Experience of employees with less than 2 years to 2. 
15. Normalize the Salary column so that all values are between 0 and 1. 
16. Replace all Location values with "Remote" for employees with a Performance Score below 3. 
17. Create a new column Experience Level with values "Junior", "Mid", or "Senior" based on the 
Experience. 
18. Add a new row with specific values using the append() method. 
19. Delete the column Session from the DataFrame. 
20. Delete rows where the Age is greater than 60. 
21. Add a new column Age Group with values "Young", "Middle-aged", or "Senior" based on Age. 
22. Identify all columns with missing values using the isna() method. 
23. Fill the missing values in Performance Score with the average score of that column. 
24. Drop all rows with missing values using the dropna() method. 
25. Replace missing values in Performance Score with the median of the scores, grouped by Department. 
26. Identify rows where the employee is in the "IT" department and their Age is above the average Age 
of "IT" employees 
27. Identify rows with duplicate Name and Joining Date combinations, and remove duplicates. 
28. Remove rows where the Experience value is inconsistent with the Age (e.g., Experience > Age - 18). 
29. Sort the DataFrame by Salary in descending order. 
30. Sort the DataFrame by Department and then by Joining Date in ascending order. 
31. Rank all employees by Salary within their Department and add the rank as a new column. 
32. Sort the dataset by Experience in descending order, but break ties using Performance Score in 
ascending order. 
33. Create a new DataFrame containing only employees in "HR" with a Salary above 5000. 
34. Filter out all rows where the Location is "Chicago". 
35. Delete all rows where the Performance Score is below 2. 
36. Find the average Salary for each Department. 
37. Calculate the total Salary of all employees grouped by Status. 
38. Find the maximum Performance Score for employees in each Location. 
39. Calculate the total Salary paid to employees who joined in each year. 
40. Find the department with the highest average Performance Score. 
41. Count the number of employees in each Location grouped by their Session. 
42. Group employees by Status and calculate the sum, mean, and standard deviation of their Salary. 
43. Use the apply() method to create a new column Monthly Salary by dividing the Salary by 12. 
44. Use the applymap() method to convert all string values in the DataFrame to uppercase. 
45. Create a second dataset containing Department and Budget. Perform an inner join with the original 
dataset. 
46. Merge the dataset with another dataset that includes additional information about employee ID and 
their recent Projects. 
47. Perform a left join with a dataset containing Department and Team Lead details, adding Team Lead 
to the DataFrame. 
48. Create a DataFrame with employee ID and Project Count, then merge it with the original dataset. 
Calculate the average Salary per project. 
49. Calculate the percentage increase in Salary for each employee compared to the average Salary in 
their Department. 
50. Print “Thanks”
