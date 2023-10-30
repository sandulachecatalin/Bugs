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

**Bug #7: Broken Internal Image on Evenimente Page - https://www.primariatechirghiol.ro/**

**Priority and severity:**
P1 - Low

**Description:**
While browsing the website Home - Primaria Techirghiol , specifically on the "Evenimente" page Evenimente Archives - Primaria Techirghiol , I encountered an issue where an internal image is broken. The URL of the broken image is https://www.primariatechirghiol.ro/wp-content/themes/portal/includes/timthumb.php?src=https://www.primariatechirghiol.ro/wp-content/themes/portal/images/image-pending.gif&h=100&w=100&zc=1.

**Steps to Reproduce:**
1. Navigate to the "Evenimente" page on the website Evenimente Archives - Primaria Techirghiol .
2. Observe the page content, specifically looking for images related to events.

**Expected Behavior:**
Images on the "Evenimente" page should load correctly, enhancing the user experience and providing visual context for the events listed.

**Actual Behavior:**
An internal image is broken and is not displayed correctly. The URL of the broken image is https://www.primariatechirghiol.ro/wp-content/themes/portal/includes/timthumb.php?src=https://www.primariatechirghiol.ro/wp-content/themes/portal/images/image-pending.gif&h=100&w=100&zc=1.

------------------------------

**Bug #8: Broken Links on PrimariaTechirghiol Website - https://www.primariatechirghiol.ro/**

**Priority and severity:**

**P2 - Medium**
 
**Description:**
While reviewing the website Home - Primaria Techirghiol , I identified two broken links that are not functioning as intended. The specific broken links are:
https://www.primariatechirghiol.ro/feed/
https://www.primariatechirghiol.ro/wp-content/themes/portal/petitie_persoana_fizica.php

**Steps to Reproduce:**
1. Navigate to the website Home - Primaria Techirghiol.
2. Attempt to access the URLs mentioned above.

**Expected Behavior:**
Links on the website should direct users to the intended pages or resources without errors.

**Actual Behavior:**
Clicking on the provided links results in errors or pages not loading as expected.

---------------------

**Bug #9: Missing HTTPS Redirection on Juice Shop Website - https://juice-shop.herokuapp.com/#/**

**Priority and severity:**
P2 - High

**Description:**
While using the Juice Shop website OWASP Juice Shop , I noticed that there is no automatic redirection from the HTTP version to the HTTPS version of the homepage. When accessing the website using the HTTP protocol, the user is not redirected to the secure HTTPS version of the homepage, which might pose a security risk.

**Steps to Reproduce:**
Access the website using the HTTP protocol: OWASP Juice Shop .

**Expected Behavior:**
When accessing the website using the HTTP protocol, the user should be automatically redirected to the corresponding HTTPS version of the homepage to ensure a secure connection.

**Actual Behavior:**
Accessing the website using the HTTP protocol does not trigger an automatic redirection to the HTTPS version of the homepage.

--------------------

**Bug #10: Duplicate Title Tags on Multiple Pages - http://testingchallenges.thetestingmap.org/index.php**

**Priority and severity:**
P4 - Low

**Description:**
While evaluating the website Testing Challenges , I identified an issue where multiple pages have duplicate title tags. The affected pages are:
1. [Testing Challenges ](https://testingchallenges.thetestingmap.org/)
2. [Testing Challenges ](https://testingchallenges.thetestingmap.org/challenge10.php)
3. [Testing Challenges ](https://testingchallenges.thetestingmap.org/solve_the_testing_challenges.php)

**Steps to Reproduce:**
1. Navigate to the first URL: Testing Challenges .
2. Observe the title tag of the webpage.
3. Repeat the process for the second URL: Testing Challenges .
4. Observe the title tag of the webpage.
5. Repeat the process for the third URL: Testing Challenges .
6. Observe the title tag of the webpage.

**Expected Behavior:**
Each page should have a unique and descriptive title tag that accurately reflects the content of the specific page.

**Actual Behavior:**
Multiple pages on the website have identical title tags, leading to confusion and reduced usability for both users and search engines.

--------------------

**Bug #11: Security Vulnerability - Script Injection in Comment Review for "Apple Juice" Item - https://juice-shop.herokuapp.com/#/**

**Priority and severity:**
P3 - Medium

**Description:**
While browsing the Juice Shop website OWASP Juice Shop , I identified a serious security vulnerability in the comment review section for the "Apple Juice" item. An attacker appears to have injected a malicious script within a comment review, potentially exposing users to a cross-site scripting (XSS) attack.

**Steps to Reproduce:**
1. Navigate to the Juice Shop website: OWASP Juice Shop .
2. Locate the "Apple Juice" item.
3. Access the comment reviews section for the "Apple Juice" item.
4. Observe the presence of a malicious script within one of the comment reviews.

**Expected Behavior:**
Comment reviews should only display legitimate text provided by users without allowing the execution of any malicious code or scripts.

**Actual Behavior:**
A malicious script is present in one of the comment reviews for the "Apple Juice" item. This script poses a security risk to users who access the page.

------------------------------

**Bug #12: "Clouds" word Not Translated in Romanian in OpenWeatherMap API**

**Priority and Severity:**
P4 -Low

**Description:**
When using the OpenWeatherMap API to fetch forecast data for a specific city using the lang parameter set to Romanian ("ro"), the value of the "main" field for the weather condition "Clouds" is not being translated. Instead, the value "Clouds" is returned in English.

**Steps to Reproduce:**
1.Make a request to the OpenWeatherMap API's forecast5 endpoint with the following parameters:
  City: London
  lang: ro (Romanian)
  Provide the API key

**Expected Behavior:** 
The response should include weather conditions translated to Romanian, including the translation of "Clouds" to "Norii" in the "main" field.

**Actual Behavior:** 
The response contains the value "Clouds" in the "main" field instead of the expected translation.
