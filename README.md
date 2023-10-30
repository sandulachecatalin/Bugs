# Bugs

Below are some Bug Report samples that I wrote while working on previous projects.

------------
**Bug #1: About Us" section not updated or lacking relevant information - https://www.demoblaze.com/**

**Priority and severity:**
P4 - Low

**Description:**
The "About Us" section on the website appears to be outdated and does not contain relevant information. Users visiting the page are not able to get a clear understanding of the company's current mission, values, and goals due to the lack of updated content.

**Steps to Reproduce:**
1. Navigate to the homepage of the website.
2. Locate the "About Us" link in the navigation menu.
3. Click on the "About Us" link to access the respective page.

**Expected Behavior:** 
The "About Us" section should provide up-to-date information about the company, including its mission, values, history, team, and objectives. Users should be able to understand the company's identity and goals clearly.

**Actual Behavior:**
The "About Us" section displays outdated or irrelevant content that does not accurately represent the company's current state, mission, or objectives. Users are left with incomplete or inaccurate information.

-------------

**Bug #2: Security Vulnerabilities Allowing Unauthorized Access - https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login**

**Priority and severity:**
P2 - High

**Description:**
The website https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login  exhibits significant security vulnerabilities that allow unauthorized access to customer-sensitive data without proper authentication.

**Steps to Reproduce:**
1. Navigate to the website URL https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login .
2. Access the "Home" page.
3. Click on "Bank Manager Login."
4. Navigate to "Customers" without requiring any login.
5. Observe that sensitive customer data is accessible without proper authentication.

**Expected Behavior:**
Sensitive customer data should not be accessible without proper authentication and authorization.

**Actual Behavior:**
Unauthorized users can access sensitive data without proper authentication.

-------------------------------

**Bug #3: Security Vulnerabilities Allowing Unauthorized Transactions - https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login**

**Priority and severity:**
P1 - Critical

**Description:**
The website XYZ Bank  exhibits significant security vulnerabilities that allow unauthorized access to unauthorized transactions without proper authentication.

**Steps to Reproduce:**
1. Navigate to the website URL https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login .
2. Access the "Home" page.
3. Click on "Customer Login."
4. Choose a customer name.
5. Select any option that triggers a transaction.
6. Note that no password or authentication is required for the transaction.

**Expected Behavior:**
Transactions should require appropriate authentication (e.g., password, two-factor authentication) to prevent unauthorized access.

**Actual Behavior:**
Unauthorized users can perform transactions without providing necessary authentication credentials.

----------------------------------------------

**Bug #4: Typo in the Word "Withdrawl" on XYZ Bank Website - https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login**

**Priority and severity**
P4 - Low

**Description:**
While using the website https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login , I encountered a typographical error in the word "Withdrawl." The correct spelling should be "Withdrawal," but the incorrect spelling "Withdrawl" is being displayed.

**Steps to Reproduce:**
1. Navigate to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login .
2. Log in to the website using valid credentials.
3. Access a section or page where the word "Withdrawl" is present, such as a transaction or account page.

**Expected Behavior:**
The correct spelling "Withdrawal" should be used in the user interface and any textual content on the website.

**Actual Behavior:**
The incorrect spelling "Withdrawl" is being displayed in the user interface.

---------------------------

**Bug #5: Missing Image for Coffee in Consumption Calculator - https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/**

**Priority and severity:**
P2 - Medium

**Description:**
While using the Consumption Calculator on the website Consumption Calculator , I encountered a problem where the image related to coffee is not displayed when the user surpasses both the break-even numbers for both coffees and cigarettes. Instead, only an image related to cigars is presented, leading to confusion for the user.

**Steps to Reproduce:**
1. Navigate to Consumption Calculator .
2. Input values for both coffee and cigarettes such that both break-even numbers are surpassed.
3. Observe the image that is presented.

**Expected Behavior:**
When the user surpasses both the break-even numbers for coffee and cigarettes, the appropriate images for both coffee and cigarettes should be displayed. This helps in providing clear visual feedback to the user.

**Actual Behavior:**
Only the image related to cigars is displayed when the user surpasses both break-even numbers. The image related to coffee is missing, which may lead to confusion and misinterpretation.

----------------

**Bug #6: Incorrect Error Message for Cigarette Intake Calculation - https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/**

**Priority and severity:**
P2 - Medium

**Description:** 
While using the Consumption Calculator on the website Consumption Calculator , I encountered an issue where an incorrect error message is displayed when inserting 3 cigarettes with an individual nicotine content of 30mg each. The error message incorrectly states that "You have exceeded the daily maximum intake of 30 mg," which is misleading and inaccurate.

**Steps to Reproduce:**
1. Navigate to Consumption Calculator .
2. Enter the values for cigarette consumption:
3. Number of cigarettes: 3
4. Observe the error message displayed.

**Expected Behavior:** 
When entering the values for cigarette consumption as mentioned above, the error message should accurately reflect the total nicotine content based on the input values.

**Actual Behavior:** 
The error message incorrectly states that the user has exceeded the daily maximum intake of 30 mg, despite the input values not exceeding this limit.

---------------------------

