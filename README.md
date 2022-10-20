# Pewlett-Hackard-Analysis

## Project purpose
Our purpose for this challenge was to figure out the amount of employees that are retiring by finding out their title. Then after that identify which employees were eligible to be able to partake in the mentorship program. We were able to figure out the employees and their titles that are retireing by finding employees that were born from January 1, 1952 through December 31, 1955. We did this by creating a query that retrieved information of emp_no, first_name, and last_name columns form the employees table. Then we pulled the title, from_date, and to_date columns form the titles table and joined them together as a primary key and filtered the date by birth_date of the years 1952-1955 to make the retirements_title table. I had some trouble receiving the output for the retirement_title. WIth the help of my classmates in office hours I found out I didnt import all the data correctly from the csvs. After I got that sorted out and re-run the code my output finally showed that matched the challenge. The next part for deliverable 1 we created the unique_title to by using the DISTINCT ON function. The function was used to find the first time emp_no occured in the table. The last part of deliverable 1 we used the ORDER BY COUNT to pull in the total amount of employees with titles that are retiring from the unique_title table we created. In the second deliverable we created a table similar to retirements_title table but instead we changed the years to January 1, 1965 to December 31, 1965 to pull employees that can participate in the mentorship programs. Now when I ran the code to see the output for unique_title. at number 6 it showed employee Mary Sluis, Staff.. Not sure why shes at the spot. The was the only name that was not in the pic of what the table  is supposed to look like on the module challenge examples in our bootcamp. 

##Results

This was the results I got for retirement_title

![image](https://user-images.githubusercontent.com/111409181/196838974-708047af-fef7-4871-ab5c-018882912bf9.png)





This was the result I got for unique_title.


![image](https://user-images.githubusercontent.com/111409181/196838049-80d6de8c-84c4-4121-9558-f9f2eb21c074.png)



This was the result for retiring_titles


![image](https://user-images.githubusercontent.com/111409181/196840169-8e5a9eb9-a0e3-4bd1-a488-ee555a8a6872.png)




This was the result for the mentorship_eligibilty table


![image](https://user-images.githubusercontent.com/111409181/196840654-bda2aa2b-55c9-47b7-afdc-37ce97ab77db.png)


