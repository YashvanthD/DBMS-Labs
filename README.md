# DBMS-Labs

## Q1. Library Database

## Q2. Order Database

## Q3. Movies Database

## Q4. College Database

## Q5. Company Database

<hr>

### Q1. Library Database

>>>BOOK (Book_id, Title, Publisher_Name, Pub_Year)

>>>BOOK_AUTHORS (Book_id, Author_Name)

>>>PUBLISHER (Publisher_Name, Address, Phone)

>>>BOOK_COPIES (Book_id, Branch_id, No-of-Copies)

>>>BOOK_LENDING (Book_id, Branch_id, Card_No, Date_Out, Due_Date)

>>>LIBRARY_BRANCH (Branch_id, Branch_Name, Address)

*Querry*

>a)	Make a list of all project numbers for projects that involve an employee whose last name is ‘Scott’, either as a worker or as a manager of the department that controls the project.

>b)	Show the resulting salaries if every employee working on the ‘IoT’ project is given a 10 percent raise.

>c)	Find the sum of the salaries of all employees of the ‘Accounts’ department, as well as the maximum salary, the minimum salary, and the average salary in this department

>d)	Retrieve the name of each employee who works on all the projects controlled by department number 5 (use NOT EXISTS operator). 

>e)	For each department that has more than five employees, retrieve the department number and the number of its employees who are making more than Rs. 6,00,000.




### Q2. Order Database

>>>SALESMAN (Salesman_id, Name, City, Commission) 

>>>CUSTOMER(Customer_id, Cust_Name, City, Grade, Salesman_id) 

>>>ORDERS (Ord_No, Purchase_Amt, Ord_Date, Customer_id,Salesman_id) 


*quuery*

>a)	Count the customers with grades above Bangalore’s average.

>b)	Find the name and numbers of all salesmen who had more than one customer.

>c)	List all salesmen and indicate those who have and don’t have customers in their cities (Use UNION operation).

>d)	Create a view that finds the salesman who has the customer with the highest order of a day.

>e)	Demonstrate the DELETE operation by removing salesman with id 1000. All his orders must also be deleted.








### Q3. Movies Database

>>>ACTOR (Act_id, Act_Name, Act_Gender)

>>>DIRECTOR (Dir_id, Dir_Name, Dir_Phone)

>>>MOVIES (Mov_id, Mov_Title, Mov_Year, Mov_Lang, Dir_id)

>>>MOVIE_CAST (Act_id, Mov_id, Role)

>>>RATING (Mov_id, Rev_Stars)


*Querry*

>a)	List the titles of all movies directed by ‘Mani ratnam’.

>b)	Find the movie names where one or more actors acted in two or more movies.

>c)	List all actors who acted in a movie before 2010 and also in a movie after 2017 (use JOIN operation).

>d)	Find the title of movies and number of stars for each movie that has at least one rating. Sort the result by movie title.

>e)	Update rating of all movies directed by ‘Karan Johar’ to 4.



### Q4. College Database

>>>STUDENT (USN, SName, Address, Phone, Gender)

>>>SEMSEC (SSID, Sem, Sec)

>>>CLASS (USN, SSID)

>>>SUBJECT (Subcode, Title, Sem, Credits)

>>>IAMARKS (USN, Subcode, SSID, Test1, Test2, Test3, FinalIA)


*Querry*

>a)	List all the student details studying in fourth semester ‘C’ section.

>b)	Compute the total number of male and female students in each semester and in each section.

>c)	Create a view of Test1 marks of student USN ‘1SI20IS001’ in all subjects.

>d)	Calculate the FinalIA (average of best two test marks) and update the corresponding table for all students.

>e)	Categorize students based on the following criterion:

>>If FinalIA = 17 to 20 then CAT = ‘Outstanding’
>>If FinalIA = 12 to 16 then CAT = ‘Average’
>>If FinalIA< 12 then CAT = ‘Weak’
>>Give these details only for 8th semester A, B, and C section students.



### Q5. Company Database

>>>EMPLOYEE (SSN, Name, Address, Sex, Salary, SuperSSN, DNo)

>>>DEPARTMENT (DNo, DName, MgrSSN, MgrStartDate)

>>>DLOCATION (DNo,DLoc)

>>>PROJECT (PNo, PName, PLocation, DNo)

>>>WORKS_ON (SSN, PNo, Hours)

*Query*

>a)	Make a list of all project numbers for projects that involve an employee whose last name is ‘Scott’, either as a worker or as a manager of the department that controls the project.

>b)	Show the resulting salaries if every employee working on the ‘IoT’ project is given a 10 percent raise.

>c)	Find the sum of the salaries of all employees of the ‘Accounts’ department, as well as the maximum salary, the minimum salary, and the average salary in this department

>d)	Retrieve the name of each employee who works on all the projects controlled by department number 5 (use NOT EXISTS operator). 

>e)	For each department that has more than five employees, retrieve the department number and the number of its employees who are making more than Rs. 6,00,000.


