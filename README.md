# Cypress Automation Framework

This is an end-to-end automation project using Cypress with Cucumber, designed for testing modern web applications such as GreenKart.

## Project Structure

automation/
├── cypress/
│ ├── integration/ # Test files
│ ├── fixtures/ # Test data
│ ├── support/ # Commands and setup
│ └── cucumberReports/ # JSON results for Cucumber
├── package.json
├── README.md
└── .gitignore



## Scripts

Run your tests using these predefined npm scripts:

| Command                     | Description                                 |
|----------------------------|---------------------------------------------|
| `npm run test`             | Run all tests (headless)                    |
| `npm run headTest`         | Run tests in headed mode                    |
| `npm run chromeTest`       | Run tests in Chrome browser                 |
| `npm run recordDashBoardTest` | Run tests and record to Cypress Dashboard |
| `npm run GreenKartTest`    | Run all tests in `GreenKart/` folder        |
| `npm run SmokeTest`        | Run single smoke test (Test1.js)            |

Dependencies

- Cypress ^13.15.2
- Cucumber Preprocessor `@badeball/cypress-cucumber-preprocessor`
- Browserify Preprocessor
- cypress-iframe for iframe handling
- Mochawesome for HTML reports
- multiple-cucumber-html-reporter

Install

npm install
