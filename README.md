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
| 001 | Initial sign in messaging | Unauthenticated guest - non-member rate   | Tester must be unauthenticated before reaching the payment page and must select a non-member rate |.      |.       |.      |.      |.     |
| 002 | Initial sign in messaging | Unauthenticated guest - member rate   | Tester must be unauthenticated before reaching the payment page and must select a member rate |.      |.       |.      |.      |.     |
| 003 | Initial sign in messaging | Signed in member - non-member rate    | Tester must be signed in before reaching the payment page and must select a non-member rate |.      |.       |.      |.      |.     |
| 004 | Initial sign in messaging | Signed in member - member rate     | Tester must be signed in before reaching the payment page and must select a member rate |.      |.       |.      |.      |.     |
| 005 | Initial sign in messaging  | Signed out member - non-member rate    | Tester must sign in and then sign out before reaching the payment page and must select a non-member rate |.      |.       |.      |.      |.     |
| 006 | Initial sign in messaging | Signed out member - member rate    | Tester must sign in and then sign out before reaching the payment page and must select a member rate       |.      |.       |.      |.      |.     |
| 007 | Sign in messaging after state change | Unathenticated to signed in - member rate   | Tester must be unauthenticated before reaching the payment page and must select a member rate       |.      |.       |.      |.      |.     |
| 008 | Sign in messaging after state change | Signed in to signed out - member rate    | Tester must be signed in before reaching the payment page and must select a member rate       |.      |.       |.      |.      |.     |
| 009 | Sign in messaging after state change | Signed out to signed in - member rate    | Tester must have signed in and signed out before reaching the payment page and must select a member rate       |.      |.       |.      |.      |.     |
| 010 | Sign in messaging after state change | Signed out to unauthenticated - member rate    | Tester must have signed in and signed out before reaching the payment page and must select a member rate       |.      |.       |.      |.      |.     |
| 011 | Form error validation | Empty fields    | Guest information fields must be blank       |.      |.       |.      |.      |.     |
| 012 | Error messaging | First Name    | N/A       |.      |.       |.      |.      |.     |
| 013 | Error messaging | Last Name     | N/A         |.      |.       |.      |.      |.     |
| 014 | Error messaging  | Email Address    | N/A        |.      |.       |.      |.      |.     |
| 015 | Error messaging | Country/Region    | N/A         |.      |.       |.      |.      |.     |
| 016 | Error messaging | Address    | N/A        |.      |.       |.      |.      |.     |
| 017 | Error messaging | City/Town    | N/A         |.      |.       |.      |.      |.     |
| 018 | Error messaging | Country/Region   |   N/A      |.      |.       |.      |.      |.     |
| 019 | Error messaging | Postal Code    | N/A         |.      |.       |.      |.      |.     |
| 020 | Error messaging | Country/Region Code    | N/A         |.      |.       |.      |.      |.     |
| 021 | Error messaging | Phone Number    | N/A        |.      |.       |.      |.      |.     |
| 022 | Error messaging | Phone Number - invalid input    | N/A         |.      |.       |.      |.      |.     |
| 023 | Form prefill | All information prefilled    | Tester must sign into an account where all guest information is saved prior to reaching the payment page   |.      |.       |.      |.      |.     |
| 024 | Form prefill  | Partial prefill    | Tester must sign into an account where only the some guest information is saved prior to reaching the payment page      |.      |.       |.      |.      |.     |
| 024 | Form prefill  | Partial prefill    | Tester must sign into an account where only the some guest information is saved prior to reaching the payment page      |.      |.       |.      |.      |.     |
| 025 | Expand collapsed fields | Additional address information | N/A         |.      |.       |.      |.      |.     |
| 026 | Expand collapsed fields | Special Request | N/A         |.      |.       |.      |.      |.     |
| 027 | Sign in button on form | Unauthenticated guest - any rate    | Tester must be unathenticated before reaching the payment page       |.      |.       |.      |.      |.     |
| 028 | Sign in button on form | Signed out member - any rate    | Tester must sign in and sign out before reaching the payment page       |.      |.       |.      |.      |.     |
| 029 | Not You? button on form | Signed out member - any rate    | Tester must sign in and sign out before reaching the payment page       |.      |.       |.      |.      |.     |
| 030 | External Links on form | T&Cs and Privacy Statement - Unauthenticated or Signed out - member rate    | Tester must be either unauthenticated or signed out and must select a member rate     |.      |.       |.      |.      |.     |
| 031 | Sign up during booking checkbox |  Unauthenticated or Signed out - member rate    | Tester must be either unauthenticated or signed out and must select a member rate     |.      |.       |.      |.      |.     |



