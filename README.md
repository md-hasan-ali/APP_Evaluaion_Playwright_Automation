
# Project Title

## Overview

This project evaluates expertise in Playwright, Automated Testing, Page Object Model (POM), and overall code quality. The focus is on automating test cases for a simulated project management application, specifically CRUD operations.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Installation](#installation)
3. [Running Tests](#running-tests)
4. [Test Report](#report)


## Project Structure

```plaintext
project-directory
│
├── tests
│   ├── loginTest.spec.js
│   ├── ProjectOperations.spec.js
│   ├── TaskOperations.spec.js
│
├── pages
│   ├── HomePage.js
│   ├── LoginPage.js
│   ├── ProjectPage.js
│   ├── TaskPage.js
│
├── utils
│   ├── locators.js
│   ├── testuserConfig.js // User credentials
│
├── playwright.config.js
├── package.json
└── README.md
```


Installation
Prerequisites
    1. Node.js installed
    2. npm (comes with Node.js)

Steps
    Clone the repository: 

    bash

    git clone https://github.com/your-username/your-project.git

    Navigate to the project directory:
    cd your-project

Install dependencies:
    npm install
    npx playwright install

Running Tests
Execute the following command to run the tests:
    npm test

This will trigger the Playwright test suite, and the results will be displayed in the browser.