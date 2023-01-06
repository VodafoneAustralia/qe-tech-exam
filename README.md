# Quality Engineer - Technical Exam

Welcome to our Quality Engineering Technical Exam. The purpose of this exam allows you to demonstrate your skills and show us why you are the one.

## API & UI Automation Exam

Develop a UI & API test automation framework and create tests within this framework as outlined below:

1. Visit TPG's IINET NBN Plans page https://www.iinet.net.au/home
2. Click `View 5G plans` button in the homepage
3. Send a **GET request** to https://pc.iinet.net.au/product-configurator/api/fixedwireless/IINET?planType=new&technology=5G
4. Validate **if all details of all plans in the UI matches with the result found in Step 3** (details found under `[plans]`)
5. Click any of the available plans
6. Validate **if the price shown is the same with the price displayed in the floating bar** (shown at the bottom of the screen) and **if all details are correctly being displayed at the bottom of the page**
7. At the bottom of the page, where the price and details of the plan is displayed, **take a screenshot** and **save the result to a folder** using an automated script
8. **Redo Step 5-7** and do the same to the other plans until all plans are validated


## Guidelines & Submission Requirements

Use **your preferred programming language and tool**. However, we highly prefer **Cypress** and programming language is **Javascript** 

### Steps

- Create your own Github repository
- Create a README.md file explaining how to execute your test 
>Please note that if we cannot run your test using just your README file, this would fail the test
- Sign up to any free CI tool such as Github Actions, Gitlab, CircleCI etc. Run your test in the CI and share the result url with us
- Ensure code is written neatly showcasing reusability and easy maintainability of tests
- Complete within 3 days of receiving the test
