# Test Plan: Phonebook
1. Test Objective
Verify the correct functionality of the Phonebook web application: availability, navigation, functionality, UI, as well as form validation and error handling.

2. Areas to be Tested
Home page
About page
Login/Registration page
Data input (email, password)
UI element display: headers, buttons, input fields
Error handling (e.g., registration fails with code 400)
Network requests (analyzed via DevTools)

3. Areas Not to be Tested
Performance
Mobile responsiveness
Backend implementation and API security
Multilanguage support

4. Test Strategy

Types of Testing:
Functional testing
UI/UX testing
Input and validation testing
Negative scenarios testing (e.g., invalid email)

Methods:
Manual testing
Using DevTools for network analysis

5. Criteria
Acceptance Criteria:
All main functions (login, registration, page display) work correctly
Errors are displayed properly

Test Start Criteria:
Application deployed in test environment

Test Completion Criteria:
≥ 95% of planned test cases executed
No critical/blocking bugs
Final test report prepared

6. Resources
1 QA engineer

Test Environment:
Device: PC
OS: Windows 10 64-bit
Browser: Chrome v137.0.0.0
Resolution: 1265 x 593
Tools: DevTools

7. Schedule
Testing duration: 2 days

8. Roles and Responsibilities
QA Engineer: prepare test cases, execute tests, report bugs

9. Risk Assessment
Application does not load / unavailable
Registration fails (e.g., error 400)
No feedback on errors
UI elements (buttons, headers) not displayed

10. Documentation
Test Plan
