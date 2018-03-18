# ContactManagement
To run application, you will need to download index.html file and run it in browser.
This project is developed using Extjs Javascript framework.
I have used Extjs6 library using CDN path. So to run this application, internet is needed.

Application details-

1)Contact form 
-It is used to add new contact record
-It is used to update existing record

2)List of Contacts
-It displays all contacts in grid.

Steps=
1) To create new contact, fill out fields on Contact form. 
   First name and last name allows only alphabates
   Email requires value in format of "abc@gmail.com"
   Phone number allows only numbers and maxlength should be 10
   
   If one of above criteria is missed, then contact cannot be added. 
   Clicking on new record , inserts that contact in grid.
   
2) You can update existing record by clicking on grid row.
   Once record is seleted for update action, its values get loaded in contact form. And also 'Update changes' button gets enabled.
   After modification is done, record get updated and these updated values get displayed in grid also.
   
3) You can delete record by clicking on Delete button.
