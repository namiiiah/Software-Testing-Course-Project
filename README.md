# **Pinterest Website Testing Project**

## **Overview**
This project tests the **Pinterest website** ([https://www.pinterest.com/](https://www.pinterest.com/)) using **Selenium IDE** as a school assignment. It validates core features like **login**, **registration**, **search**, **saving pins**, **board creation**, **following accounts**, **logout**, and **profile editing**. Test scripts are stored in the **`SeleniumIDE-tests`** folder as **`.side`** files, aligned with **`TestCase.xlsx`**.

## **Prerequisites**
- **Selenium IDE**: Microsoft Edge extension ([https://www.selenium.dev/selenium-ide/](https://www.selenium.dev/selenium-ide/)).
- **Browser**: Latest **Microsoft Edge**.
- **Pinterest Account**: For authenticated tests.
- **Excel**: To view **`TestCase.xlsx`**.
- **Internet**: Stable connection.

## **Repository Structure**
- **`TestCase.xlsx`**: Test cases for:
  - **TC_Login**: Valid/invalid credentials, Google login.
  - **TC_Register**: Account registration scenarios.
  - **TC_Search**: Keyword searches, filters, suggestions.
  - **TC_Save**: Saving pins to boards.
  - **TC_CreateBoard**: Board creation, name validation.
  - **TC_Follow**: Following/unfollowing accounts.
  - **TC_Logout**: Logout, session management.
  - **TC_EditProfile**: Profile editing (name, bio, etc.).
  - **Includes**: Summary (bugs, pass/fail/pending) and test details (ID, steps, input, expected result, priority, status).
- **`SeleniumIDE-tests/`**: **`.side`** files for each test case (e.g., **`tc_login_001.side`**).
- **`screenshots/`**: Evidence of test execution and defects.
- **`bug_reports/`**: Defect reports for failed test cases.

## **Key Test Cases**
- **TC_Login_019**: Failed login with valid phone number.
- **TC_Login_018**: Failed login with Caps Lock enabled.
- **TC_Search_017**: Failed image search capability.
- **TC_Search_009**: Failed click on search suggestion.
- **TC_Register_016**: Failed anti-automated registration (CAPTCHA).
- **TC_CreateBoard_016**: Failed spam board creation.
- **TC_Follow_005**: Failed follow limit check.
- **TC_Logout_008**: Failed session cookie deletion.

## **How to Use**
1. **Review Documents**:
   - View **`TestCase.xlsx`** for test scenarios.
   - Check **`screenshots/`** for test evidence.
   - Open **`bug_reports/`** for defect reports.
2. **Run UI Tests**:
   - Install **Selenium IDE**.
   - Open **`.side`** files in **`SeleniumIDE-tests/`** (e.g., **`tc_login_001.side`**) and run.
3. **View Results**:
   - Check **Selenium IDE logs** and compare with **`TestCase.xlsx`** status.
   - Review **`screenshots/`** for visuals.
   - Check **`bug_reports/`** for defect details.

## **Achievements**
- Automated test cases for **Pinterest** features with **Selenium IDE**.
- Identified and documented defects in **`bug_reports/`** with evidence in **`screenshots/`**.
- Produced comprehensive test documentation in **`TestCase.xlsx`**.

## **Notes**
- **Testing Environment**: **Microsoft Edge** (latest) on Windows.
- **Portfolio Use**: Demonstrates automation testing skills for **Intern Tester** role.

## **Links**
- **Pinterest**: [https://www.pinterest.com/](https://www.pinterest.com/)
- **Selenium IDE**: [https://www.selenium.dev/selenium-ide/](https://www.selenium.dev/selenium-ide/)

## **Contact**
- **Email**: tamnhint0905@gmail.com
- **Date Created**: **01/07/2025**
