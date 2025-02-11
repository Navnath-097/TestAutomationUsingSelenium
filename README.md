# TestAutomationUsingSelenium

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: NAVNATH VISHNU CHAVAN

*INTERN ID*: CT08THZ

*DOMAIN*: SOFTWARE TESTING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

## DISCRIPTION OF PROJECT:

Automating the given web application's Login and Navigation functionality along with
automating all web-elements using selenium webdriver and java.

To do this task I am using Textract which is Java, Selenium, Page Object Model, and for assertion TestNG, for build management Maven in which all the dependincies are kept in pom.xml file.
I have wrote almost 21 test scripts and automated them by using selenium.
In this project I have used page object model, in which common tasks like initiating browser by using @berforMethod and closing browser by using @AfterMethod
are kept in common package. Then the tests scripts are written in separate classes with @Test anotation and connetcted those classes with common class in which @Befor and @After methods are present
by using "extends" keyword. Finally I have created a testng.xml in which I have mentioned all test cases to run them one by one and after running them I have generated report whish is as follws:

## Here is a summary of the test execution report:

### Test Execution Summary:

- **Total Tests Executed:** 18  
- **Passed Tests:** 15  
- **Failed Tests:** 3  
- **Skipped Tests:** 0  
- **Retried Tests:** 0  
- **Total Execution Time:** 386,499 ms  

### **Failed Test Cases:**
1. **TC_002_CheckLogo**  
   - **Issue:** Assertion failed (Expected `true` but found `false`).  
   - **Location:** `checkLogo` method in `CheckLogo.java`  

2. **TC_010_CheckFooterLink_Functional**  
   - **Issue:** Assertion failed (Expected `true` but found `false`).  
   - **Location:** `checkFooterLink_Functional.java`  

3. **TC_018_OrangeHRM_YouTube_Functional**  
   - **Issue:** Assertion failed (Expected `true` but found `false`).  
   - **Location:** `YouTube_Functional.java`  

### **Passed Test Cases:**
All other 15 test cases passed successfully, including:
- **Login Tests**
- **Password Validation**
- **Social Media Links (LinkedIn, Facebook, Twitter)**
- **Button and UI Validations**

### **Observations:**
- The majority of the tests passed successfully, indicating a stable automation framework.
- The failures are related to **logo and footer link verification** as well as **YouTube integration** in OrangeHRM.
- The root cause appears to be **incorrect expectations in assertions** or **UI elements not found**.

### **Next Steps:**
1. Investigate the failures by debugging the failed test cases.
2. Validate if the expected elements are present on the UI.
3. Ensure the automation scripts are properly synchronized with the webpage loading times.
4. If necessary, update locators or assertion conditions to match the actual UI behavior.

![Image](https://github.com/user-attachments/assets/ddd8be72-2cea-4f77-a91b-81edb0fc49f8)
