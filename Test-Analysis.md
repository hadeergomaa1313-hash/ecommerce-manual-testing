# Test Analysis – nopCommerce

## 1. Feature: User Registration

### Objective
To analyze the user registration functionality and identify the conditions that need to be tested.

### Test Basis
The registration form and its available fields on the nopCommerce demo website.

### Test Conditions

| ID | Test Condition | Expected Behavior |
|---|---|---|
| REG-TCND-01 | Register with valid required information | The account should be created successfully if all requirements are met. |
| REG-TCND-02 | Submit the form with required fields empty | The website should display appropriate validation messages. |
| REG-TCND-03 | Register using an email address that is already registered | The website should prevent duplicate registration and display an appropriate message. |
| REG-TCND-04 | Enter an invalid email format | The website should display an email validation message. |
| REG-TCND-05 | Enter mismatching password and confirmation password | The website should display an appropriate validation message. |

### Notes
These test conditions are initial analysis items. They should be reviewed against the actual registration form and observed website behavior before test case design.
