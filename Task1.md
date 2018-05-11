1.Test Case: [Correct data] The user registers using the correct data.

Steps: 1 Fill in all fields of the form with data in the correct format.
       2. Click on the Register  Button
Expected result: The user is correctly registered

2.Test Case: [No data available] The user registers without entering the data in the form fields	

Steps: 1. Skip completion of form fields
       2. Click on the Register Button
Expected result: The user is not registered. You will be prompted to complete the required fields.
			
3.Test Case: [Wrong email] You register by entering the wrong email address format and correct password.
	
Steps: 1. Enter text that is not an email address in the field of the email form, e.g. "test1234.com", "test@123com", "@gmail.com", "test21@gmail".	
       2. Fill in the remaining fields of the form correctly 
       3. Click on the Register Button
Expected result: The user is not registered. The validator is displayed with information about an incorrectly entered email address. 	
			
4.Test Case [Incorrect password] You register by entering the wrong password.

Steps: 1. Enter a text in the Password field that does not meet at least one of the following conditions
       2. Enter the same text in the Confirm Password field
       3. Fill in the remaining fields of the form correctly
       4. Click on the Register Button
Expected result: The user is not registered. A validator is displayed with information about an incorrectly entered password.	
 				
5.Test Case [Wrongly repeated password] You register by repeating the password incorrectly.

Steps: 1. Enter the data correctly in the Email, Password, Last Name fields.
       2. Enter a different password in the Confirm Password field	
       3. Click on the Register Button
Expected result: The user is not registered. A validator is displayed to indicate that the password has not been repeated correctly.	
					
6.Test Case [An occupied email address] You register by entering an email address that is occupied by another user.

Prerequisite: Register the new user correctly
Steps: 1. Enter an address into the email field that you have already created for the account.	
       2. Fill in the remaining fields of the form with new data
       Enter the password correctly in the "Repeat password" field	
       3. Click on the Register Button
Expected result: The user is not registered. The message "The user with the specified e-mail address is already registered" is displayed.			

7.Test Case [Incomplete form] You register by submitting a form that is not fully completed.

Steps: 1. Fill in the form leaving the fields blank (try different combinations).
       2. Click on the Register Button
Expected result: The user is not registered. You will be prompted to complete the required fields.

8.Test Case [Password validation] Check the password limit when enter value less than min.

Steps: 1. Enter value which is alphanumeric but less than min. (e.g. 'Password')
       2. Click on Register Button
Expected result: It should show validation message

9.Test Case [Password validation] Check the password limit when enter value greater than max.

Steps: 1. Enter value which is alphanumeric but more than max. (e.g. "nanacommcjfkid434adasdasdasdasd3243dsadadsad432423'.
       2. Click on Register Button
Expected result: It should show validation message

10.Test Case [Password validation] Check the password when pass only numbers/letters/special characters.

Steps: 1. Enter value in numbers/special characters which is in between min.-max. 
       2. Click on Register Button
Expected result: It should show validation message if some of this are invalid

11.Test Case [Last Name Validation] Check the Last Name when pass only numbers/special characters.

Steps: 1. Enter value in numbers/special characters which is in between min.-max. 
       2. Click on Register Button
Expected result: It should show validation message

12.Test Case [Last Name Validation] Check the Last Name limit when enter value less than min.

Steps: 1. Enter value which is less than min. (e.g. "K")
       2. Click on Register Button
Expected result: It should show validation message

13.Test Case [Last Name Validation] Check the limit when enter value greater than max.

Steps: 1. Enter value which is more than max. 
       2. Click on Register Button
Expected result: It should show validation message

14.Test Case [Last Name Validation] Check the Last Name when not start with capital letter

Steps: 1 Enter value which is start without capital letter
       2. Click on Register Button
Expected result: It should show validation message

