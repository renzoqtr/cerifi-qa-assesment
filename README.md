# QA Automation Assessment

Welcome to the QA Automation assessment. Please follow the instructions below to complete the exercise:

## Preparation

1. **Demo Page**: Use the SauceDemo application at [https://www.saucedemo.com/](https://www.saucedemo.com/).

2. **Fork and Clone**:
   - Fork this repository to your GitHub account.
   - Clone the forked repository to your local machine.

3. **Create a Branch**:
   - Create a new branch named `qa-assessment`.

4. **Write Your Scripts**:
   - Write your Cypress test scripts in the `cypress/e2e` folder.

5. **Commit and Push**:
   - Commit your changes with a meaningful message.
   - Push your branch to your GitHub repository.

6. **Pull Request**:
   - Submit a pull request to the original repository.

## Assessment Tasks

### Basic Script:
1. **Login with Standard User**:
   - Write a test to verify page load and basic interactions on the SauceDemo login page using the `standard_user` account.

### Intermediate Script:
1. **Cart and Checkout**:
   - Write a test to handle adding items to the cart and completing the checkout process using the `standard_user` account.

### Advanced Script:
1. **Comprehensive User Journey**:
   - Write a comprehensive test suite for a user journey using the `standard_user` account, utilizing custom commands and fixtures.

### Additional Exercises Based on Account Types:

#### Locked Out User:
1. **Login Failure**:
   - Write a test to attempt login with the `locked_out_user` account and verify the error message displayed.

#### Problem User:
1. **UI Validation**:
   - Write a test to login with the `problem_user` account and verify if any UI elements are misaligned or broken.

#### Performance Glitch User:
1. **Performance Check**:
   - Write a test to login with the `performance_glitch_user` account and verify if the page load times are significantly slower, and assert that actions still complete successfully.

Good Luck!
