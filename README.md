# DBMS-Labs

### Q1. Library Database

>>>BOOK (Book_id, Title, Publisher_Name, Pub_Year)

>>>BOOK_AUTHORS (Book_id, Author_Name)

>>>PUBLISHER (Publisher_Name, Address, Phone)

>>>BOOK_COPIES (Book_id, Branch_id, No-of-Copies)

>>>BOOK_LENDING (Book_id, Branch_id, Card_No, Date_Out, Due_Date)

>>>LIBRARY_BRANCH (Branch_id, Branch_Name, Address)



### Q2. Order Database

>>>SALESMAN (Salesman_id, Name, City, Commission) 

>>>CUSTOMER(Customer_id, Cust_Name, City, Grade, Salesman_id) 

>>>ORDERS (Ord_No, Purchase_Amt, Ord_Date, Customer_id,Salesman_id) 






### Q3. Movies Database

>>>ACTOR (Act_id, Act_Name, Act_Gender)

>>>DIRECTOR (Dir_id, Dir_Name, Dir_Phone)

>>>MOVIES (Mov_id, Mov_Title, Mov_Year, Mov_Lang, Dir_id)

>>>MOVIE_CAST (Act_id, Mov_id, Role)

>>>RATING (Mov_id, Rev_Stars)




### Q4. College Database

>>>STUDENT (USN, SName, Address, Phone, Gender)

>>>SEMSEC (SSID, Sem, Sec)

>>>CLASS (USN, SSID)

>>>SUBJECT (Subcode, Title, Sem, Credits)

>>>IAMARKS (USN, Subcode, SSID, Test1, Test2, Test3, FinalIA)





### Q5. Company Database

>>>EMPLOYEE (SSN, Name, Address, Sex, Salary, SuperSSN, DNo)

>>>DEPARTMENT (DNo, DName, MgrSSN, MgrStartDate)

>>>DLOCATION (DNo,DLoc)

>>>PROJECT (PNo, PName, PLocation, DNo)

>>>WORKS_ON (SSN, PNo, Hours)
