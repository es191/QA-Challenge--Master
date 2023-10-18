# QA-Challenge--Master

Bug-Finding Challenge README

## Overview

This repository contains the results of a Bug-Finding Challenge as part of the QA evaluation for Paylocity. The challenge focused on identifying defects, flaws, and issues in both the UI and API of the Benefits Dashboard application.

## Challenge Description

One of the critical functions provided for clients is the ability to pay for their employees' benefits packages, including deductions from their paychecks. The challenge involved identifying as many bugs, defects, and flaws as possible in the Benefits Dashboard application and creating a detailed report similar to what would be presented to developers.

## User Story

As an Employer, I want to input my employee data so that I can get a preview of benefit costs.

## Acceptance Criteria

#### Scenario 1: Add Employee

Given an Employer
And I am on the Benefits Dashboard page
When I select Add Employee
Then I should be able to enter employee details
And the employee should save
And I should see the employee in the table
And the benefit cost calculations are correct

#### Scenario 2: Edit Employee

Given an Employer
And I am on the Benefits Dashboard page
When I select the Action Edit
Then I can edit employee details
And the data should change in the table

#### Scenario 3: Delete Employee

Given an Employer
And I am on the Benefits Dashboard page
When I click the Action X
Then the employee should be deleted

## How to Use

1. Ensure you have Postman installed on your machine.

2. Clone the Repository

3. Import the Postman Collection

- Open Postman.

- Click on "File" > "Import" and select the Postman collection file provided in the repository.

4. Run the Tests

- In Postman, select the imported collection from the left sidebar.

- Click the "Run" button to execute the tests.

Postman will execute the tests, and the results will be displayed in the Postman Runner. You can view the test results and any associated requests and responses.

## Bug Reports

Bug report is attached in the mail.
