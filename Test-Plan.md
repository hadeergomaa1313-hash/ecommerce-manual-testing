# Test Plan – nopCommerce Demo Website

## 1. Project Overview

**Project Name:** nopCommerce Demo Website

**Website URL:** https://demo.nopcommerce.com/

**Testing Type:** Manual Testing

**Project Type:** E-commerce Website

### Test Objective

The objective of this testing project is to verify that the main e-commerce functionalities work as expected, identify defects, and document the test results.

## 2. Test Scope

### In Scope

The following functionalities will be tested:

- User Registration
- User Login and Logout
- Product Catalog
- Product Search
- Product Details
- Shopping Cart
- Checkout Process
- Required Field Validation
- Error Messages and Input Validation

### Out of Scope

- Real payment processing
- Performance and load testing
- Security penetration testing
- Automated testing
- Third-party services that cannot be accessed or controlled during testing

## 3. Test Approach

Manual testing will be performed using the website's user interface.

The testing activities will include:

- Requirement and functionality review
- Test scenario identification
- Test case design
- Test data preparation
- Test execution
- Actual and expected result comparison
- Defect reporting
- Defect retesting
- Regression testing
- Test summary reporting

Black-box test design techniques may be used where applicable, including equivalence partitioning and boundary value analysis.

## 4. Test Environment

| Item | Details |
|---|---|
| Application | nopCommerce Demo Website |
| Environment | Public demo website |
| Testing Type | Manual Testing |
| Browser | Google Chrome |
| Operating System | Windows |
| Test Management | GitHub / Markdown documents |
| Defect Tracking | GitHub Issues or a defect report document |

## 5. Test Schedule

The following schedule is a proposed plan for this practice project. Actual dates and durations may change depending on progress and the demo website's availability.

| ID | Task Name | Task Scope | Duration | Predecessors | Work | Start | Finish | Resource Name |
|---|---|---|---|---|---|---|---|---|
| 1 | Test Preparation Review | Review project information and website functionality | 1 day | None | 6 hours | TBD | TBD | QA Tester |
| 2 | Test Scope Definition | Identify in-scope and out-of-scope features | 1 day | 1 | 6 hours | TBD | TBD | QA Tester |
| 3 | Test Planning | Define the testing approach and activities | 1 day | 2 | 6 hours | TBD | TBD | QA Tester |
| 4 | Risk Assessment | Identify possible testing risks and limitations | 1 day | 3 | 6 hours | TBD | TBD | QA Tester |
| 5 | Test Environment Preparation | Check website access and prepare the browser | 1 day | 3 | 3 hours | TBD | TBD | QA Tester |
| 6 | Test Analysis | Review features and identify test conditions | 1 day | 3 | 6 hours | TBD | TBD | QA Tester |
| 7 | Create Registration Test Cases | Design registration test cases | 1 day | 6 | 6 hours | TBD | TBD | QA Tester |
| 8 | Create Login Test Cases | Design login and logout test cases | 1 day | 6 | 6 hours | TBD | TBD | QA Tester |
| 9 | Create Product Search Test Cases | Design product search test cases | 1 day | 6 | 6 hours | TBD | TBD | QA Tester |
| 10 | Create Product Details Test Cases | Verify product information and details | 1 day | 6 | 6 hours | TBD | TBD | QA Tester |
| 11 | Create Shopping Cart Test Cases | Design cart and quantity test cases | 1 day | 6 | 6 hours | TBD | TBD | QA Tester |
| 12 | Create Checkout Test Cases | Design checkout and required-field test cases | 1 day | 6 | 6 hours | TBD | TBD | QA Tester |
| 13 | Test Case Review | Review test cases for clarity and coverage | 1 day | 7–12 | 6 hours | TBD | TBD | QA Tester |
| 14 | Test Data Preparation | Prepare valid and invalid test data | 1 day | 13 | 4 hours | TBD | TBD | QA Tester |
| 15 | Test Execution – Registration and Login | Execute registration and login test cases | 1 day | 5, 14 | 6 hours | TBD | TBD | QA Tester |
| 16 | Test Execution – Product and Search | Execute product and search test cases | 1 day | 5, 14 | 6 hours | TBD | TBD | QA Tester |
| 17 | Test Execution – Cart and Checkout | Execute cart and checkout test cases | 1 day | 5, 14 | 6 hours | TBD | TBD | QA Tester |
| 18 | Defect Reporting | Document defects found during execution | 1 day | 15–17 | 6 hours | TBD | TBD | QA Tester |
| 19 | Test Execution Review | Review results and execution coverage | 1 day | 18 | 4 hours | TBD | TBD | QA Tester |
| 20 | Defect Retesting | Retest defects after fixes, if fixes are available | 1 day | 19 | 4 hours | TBD | TBD | QA Tester |
| 21 | Regression Testing | Check related functionality after changes | 1 day | 20 | 6 hours | TBD | TBD | QA Tester |
| 22 | Evaluate Exit Criteria | Check whether planned testing activities are complete | 1 day | 21 | 3 hours | TBD | TBD | QA Tester |
| 23 | Test Summary Report | Summarize test execution and defect results | 1 day | 22 | 4 hours | TBD | TBD | QA Tester |
| 24 | Test Closure | Organize final test documents and close the project | 1 day | 23 | 3 hours | TBD | TBD | QA Tester |

## 6. Entry Criteria

Testing can start when:

- The test plan and test scope have been defined.
- The demo website is accessible.
- The required test environment is available.
- Initial test cases and test data are prepared.

## 7. Exit Criteria

Testing activities can be considered complete when:

- All planned test cases have been executed, or any remaining cases are documented.
- Actual results have been recorded.
- Identified defects have been documented.
- Retesting and regression testing have been performed where applicable.
- A test summary report has been prepared.
- Any limitations or untested features have been documented.

## 8. Risks and Mitigation

| Risk | Impact | Mitigation |
|---|---|---|
| Demo website downtime | Testing may be interrupted | Retry later and document the interruption |
| Existing demo data | Test results may be affected by previous data | Use unique test data where possible |
| Email verification limitations | Registration verification may not be testable | Document the limitation and test available behavior |
| Checkout restrictions | Some checkout steps may be unavailable | Test accessible steps and record limitations |
| Website changes | Test results may differ over time | Record the testing date and observed behavior |

## 9. Deliverables

The following documents will be produced as part of this project:

- Test Plan
- Test Scenarios
- Test Cases
- Test Data
- Defect Reports
- Test Execution Results
- Regression Testing Checklist
- Test Summary Report

## 10. Test Execution and Defect Management

Each test case will be executed and assigned a result:

- **Pass:** The actual result matches the expected result.
- **Fail:** The actual result differs from the expected result.
- **Blocked:** The test cannot be completed because of a dependency or limitation.
- **Not Run:** The test has not been executed.

When a defect is identified, it will be documented with a unique ID, title, steps to reproduce, expected result, actual result, severity, priority, and supporting evidence when available.

## 11. Test Completion

At the end of the project, the test results will be reviewed and summarized. The report will include the number of executed, passed, failed, and blocked test cases, along with the defects identified and any testing limitations.

The project will be considered complete when the planned testing activities and documentation have been completed or any outstanding items have been clearly documented.
