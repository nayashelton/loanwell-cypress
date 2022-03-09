# loanwell-cypress
Cypress coding challenge for LoanWell

**Baseline Goal** (This is the minimum viable result and is a must-have for this challenge.)

- Choose Website to Test
- Write Test Cases for a Particular Feature or Section of the Website
- Write a Single Automated Test to provide coverage for 1 of your test cases
- Upload the Automated Test Script and/or Repo
- Record video of the Automated Test Passing

**Date & Time Accomplished -**

**Hours Worked on this Goal -**

**Mid-range Goal**

- Everything in Baseline, plus...
- Write 1+ Automated Tests to provide coverage for 3-5 of your test cases

**Date & Time Accomplished -** 

**Hours Worked on this Goal -**

**Stretch Goal**

- Everything in Mid-range, plus...
- Impress us by writing an automated test that covers a particularly difficult or complex test case

**Date & Time Accomplished -** 

**Hours Worked on this Goal -**

----------------------------------------------------------
### 1. OBJECTIVE
The following test cases will check for functionality regressions in the Guest Information form on the IHG Payment page. The contents of the form and editable field options should vary based on the type of hotel rate selected and the type of customer (Unathenticated Guest, signed in member, signed out member).

### 2. SCOPE


### 3. REGRESSION TESTS

| ID | Test Scenario | Test Case | Pre-Condition | Test Steps | Test Data | Expected Result | Actual Result | Status P/F |
|----|---------------|-----------|---------------|------------|-----------|-----------------|---------------|------------|
| 001 | Initial sign in messaging | Unauthenticated guest - non-member rate   |.       |.      |.       |.      |.      |.     |
| 002 | Initial sign in messaging | Unauthenticated guest - member rate   |.       |.      |.       |.      |.      |.     |
| 003 | Initial sign in messaging | Signed in member - non-member rate    |.       |.      |.       |.      |.      |.     |
| 004 | Initial sign in messaging | Signed in member - member rate     |.       |.      |.       |.      |.      |.     |
| 005 | Initial sign in messaging  | Signed out member - non-member rate    |.       |.      |.       |.      |.      |.     |
| 006 | Initial sign in messaging | Signed out member - member rate    |.       |.      |.       |.      |.      |.     |
| 007 | Sign in messaging after state change | Unathenticated to signed in - member rate   |.       |.      |.       |.      |.      |.     |
| 008 | Sign in messaging after state change | Signed in to signed out - member rate    |.       |.      |.       |.      |.      |.     |
| 009 | Sign in messaging after state change | Signed out to signed in - member rate    |.       |.      |.       |.      |.      |.     |
| 010 | Sign in messaging after state change | Signed out to unauthenticated - member rate    |.       |.      |.       |.      |.      |.     |
| 011 | Form error validation | Empty fields    |.       |.      |.       |.      |.      |.     |
| 012 | Error messaging | First Name    |.       |.      |.       |.      |.      |.     |
| 013 | Error messaging | Last Name     |.       |.      |.       |.      |.      |.     |
| 014 | Error messaging  | Email Address    |.       |.      |.       |.      |.      |.     |
| 015 | Error messaging | Country/Region    |.       |.      |.       |.      |.      |.     |
| 016 | Error messaging | Address    |.       |.      |.       |.      |.      |.     |
| 017 | Error messaging | City/Town    |.       |.      |.       |.      |.      |.     |
| 018 | Error messaging | Country/Region   |.       |.      |.       |.      |.      |.     |
| 019 | Form error validation | Postal Code    |.       |.      |.       |.      |.      |.     |
| 020 | Form error validation | Country/Region Code    |.       |.      |.       |.      |.      |.     |
| 021 | Form error validation | Phone Number    |.       |.      |.       |.      |.      |.     |
| 022 | Form error validation | Phone Number - invalid input    |.       |.      |.       |.      |.      |.     |
| 023 | Form prefill | All information prefilled    |.       |.      |.       |.      |.      |.     |
| 024 | Form prefill  | Partial prefill    |.       |.      |.       |.      |.      |.     |




