1. Is it possible to insert, update and delete within one select statement? If so, how can we do that? Provide an example for your answer. - 10 points

2. What is the difference between LEAD and LAG functions? Explain different types of arguments that we can pass to these functions in detail. Using your example tables, show the usage of these functions.  - 10 Points

3. Explain the below terms with an example– 

a) PL/SQL Anonymous Block - 4 points

b) Cursor - 4 points

c) Pl/Sql parameter modes (IN, OUT, INOUT) - 4 points

d) Different types of triggers - 4 points

e) Cartesian join - 4 points

 

4. Create procedure with appropriate arguments to perform updates and inserts on department table (Department name will be unique). Make sure to upload script execution test cases for all the combinations to prove the validation is successfully working and upload screenshots for each question proving the test cases.

A. CREATE DEPT TABLE AND INSERT 6 RECORDS INTO IT (refer to Instructions for Schema) - 6 points

B. INSERT THE DEPARTMENT IF NAME DOESN'T EXISTS - 6 points

C. UPDATE THE DEPARTMENT LOCATION IF NAME EXISTS - 6 points

D. RAISE ERROR IF THE DEPARTMENT NAME IS INVALID (NULL, ZERO LENGTH) - 6 points

E. RAISE ERROR IF THE DEPARTMENT NAME IS A NUMBER - 6 points

F. ACCEPTED LOCATIONS SHOULD BE AS BELOW - 6 points

                MA, TX, IL, CA, NY, NJ, NH, RH

G. DEPARTMENT ID SHOULD BE AUTO-GENERATED - 6 points

H. LENGTH OF THE DEPARTMENT NAME CANNOT BE MORE THAN 20 CHARS - 6 points

I. WHILE INSERTING THE DEPARTMENT NAME CONVERT EVERYTHING TO CAMEL CASE - 6 points

J. MAKE SURE DEPARTMENT NAME IS UNIQUE - 6 points

 

Instructions for Q4:

Create a Department table with the following columns and values and use that to run your procedure test cases:
CREATE TABLE DEPARTMENT(
           dept_id number(5) NOT NULL PRIMARY KEY,
           dept_name varchar(40) NOT NULL,
           dept_location varchar(40) NOT NULL);
Insert your own values accordingly to prove the test cases in the above table.
Department name should be unique
Fit in all the conditions in the same procedure.