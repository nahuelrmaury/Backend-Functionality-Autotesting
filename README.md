# Backend Functionality Autotesting Task

This repository contains a task focused on testing the functionality of backend services. Specifically, it involves testing the methods of the UserService (excluding CacheManagement) and the /Charge and /GetBalance endpoints of the WalletService.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Task Description](#task-description)
- [Testing Methodology](#testing-methodology)
- [Running the Tests](#running-the-tests)
- [Test Results](#test-results)

## Introduction

Testing the backend functionality of an application is crucial to ensure that it works as expected and meets the requirements. This task focuses on testing two services: UserService and WalletService, both of which have Swagger documentation available for reference.

## Prerequisites

To complete this task, you will need:

- Access to the UserService and WalletService.
- A testing tool or framework for sending HTTP requests (e.g., Postman, Swagger UI, or a testing library like `requests` in Python).
- An understanding of the methods and endpoints you are testing.

## Task Description

### Task 1: Testing UserService Methods

1. Access the Swagger documentation for the UserService.

2. Test all the methods of the UserService except for CacheManagement. Ensure that each method performs as expected and returns the correct responses.

### Task 2: Testing WalletService Endpoints

1. Access the Swagger documentation for the WalletService.

2. Test the `/Charge` and `/GetBalance` endpoints of the WalletService. Verify that these endpoints handle requests correctly and return the expected results.

## Testing Methodology

When testing each method or endpoint, consider the following:

- Test various input scenarios, including valid inputs, invalid inputs, edge cases, and boundary conditions.
- Verify the responses, including status codes, response payloads, and error handling.
- Check for proper authentication and authorization if applicable.
- Ensure that the tests are reproducible and can be automated.

## Running the Tests

1. Clone this repository to your local machine.

2. Open your preferred testing tool or framework.

3. Create test cases or requests for each method or endpoint you are testing.

4. Execute the tests, and observe the results.

## Test Results

Document the results of your tests, including any issues or unexpected behavior encountered during testing. Ensure that you provide clear and detailed feedback on the functionality of the UserService and WalletService.
