# Junit Automation Project

## Overview

This Junit WebDriver project automates the web form submission on [Digital Unite Practice Webform](https://www.digitalunite.com/practice-webform-learners). The test uploads a file with a 2MB limit, submits the form, and asserts the success message.


## Prerequisites

- Java
- ChromeDriver

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/miubat/junit-automation
    ```

2. **Set the path to your ChromeDriver executable in `FormSubmissionTest.java`.**

3. **Run the tests:**

    ```bash
    ./gradlew clean test
    ```

## Test Execution

The test performs the following steps:

1. Fills in the form fields.
2. Uploads a file.
3. Submits the form.
4. Asserts the success message.

## Test Report
![Screenshot_18](https://github.com/miubat/Junit-automation/assets/160812376/f6c0db2a-daaf-449e-abb9-398e06ec053a)



