
 
**What questions would you ask in order to clarify requirements?**


1 - Shouldn't the email field be mandatory?

2 - How long the temporary password is valid for?

3 - What happens if the load to create a user is longer than 3 seconds?

4 - The number of characters allowed at the FirstName and LastName fields are larger than those declared in the database, shouldn't the characters limit follow the same rule?

5 - Is it possible to create a user with the same input data, mainly email?

6 - Are any success or failure messages displayed to the user when clicking the Save button?

7 - What happens if the user clicks on Cancel button?

8 - What is the structure of the email sent?

9 - Must the user login using email and password?

10 - Can the user fills the FirsName and LastName with more than one value?

11 - How do we access the page to create a user?

<br /> 



**Specify 5 test cases to test this requirement**


1 - Create a user with valid data and validate the entire login flow;

2 - Create user with invalid email;

3 - Create user with email already existing in the database;

4 - Validate required fields;

5 - Validate limit and type of characters accepted in each field;
