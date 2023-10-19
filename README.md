# Bugs

Below are some Bug Report samples that I wrote while working on previous projects.

------------
**Login is not working properly**

**Description**
When trying to login with the correct credentials, nothing happens. The user is not logged in and no error message is displayed.

**Steps to reproduce**
1. Go to www.website.com/login
2. Add a correct user / pass

**Expected result**
User should be able to login and is taken to his profile page.

**Actual result**
User is not logged and and no error appears.

**Test data**
User: catalin &  Pass: 123456

-------------

**Application crash on clicking the SAVE button while creating a new user**

**Description**
Application crash on clicking the SAVE button while creating a new the user, hence unable to create a new user in the application.

**Steps to reproduce**
1. Login into the Application
2. Navigate to the Users Menu > New User
3. Filled all the user information fields
4. Clicked on the ‘Save’ button
5. Seen an error page “ORA1090 Exception: Insert values Error…”
6. See the attached logs for more information (Attach more logs related to bug..IF any)
7. And also see the attached screenshot of the error page.

**Expected Result**
On clicking SAVE button, should be prompted to a success message “New User has been created successfully”.

**Actual Result**
After clicking SAVE the application crashes.
