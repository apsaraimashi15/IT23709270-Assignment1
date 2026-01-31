# IT23709270-Assignment1
IT23709270 ITPM Assignment 1 - Playwright Automation
Student ID:IT23709270

Project Overview
This project automates functional and UI test scenarios for the SwiftTranslator (Singlish to Sinhala) web application using Playwright.

Project Structure
IT23709270/
├─ singlish-playwright/
│  ├─ package.json
│  ├─ playwright.config.js
│  └─ tests/
│     ├─ IT23709270_negative_functional.spec.ts
│     ├─ IT23709270_negative_ui.spec.ts
│     ├─ IT23709270_positive_functional.spec.ts
│     └─ IT23709270_positive_ui.spec.ts
├─ IT23709270_GitHub_Link.txt
├─ IT23709270_TestCases.xlsx
├─ package-lock.json
├─ package.json
└─ README.md

VS Code Run Instructions
Open the repository folder in VS Code.

Open a terminal and navigate to the test project:

cd singlish-playwright
Ensure Node.js is installed:

node -v
npm -v
If Node.js is not installed, download and install it from https://nodejs.org/.

Install dependencies:

npm install

Run all tests:

npx playwright test
To view the HTML report after running tests:

npx playwright show-report

Tools & Technologies
Node.js (v18+ recommended)
Playwright (end-to-end testing framework)
TypeScript (for test development)
JavaScript (for scripting and tests)
XLSX (Excel file generation for test documentation)
@types/node (TypeScript type definitions for Node.js)
HTML Reporter (Playwright built-in)
Modern browsers (Chromium, via Playwright)

Test Files
https://github.com/danajakulathunga/ITPM-Assignment-01---IT23288430-/blob/main/singlish-playwright/tests/IT23288430_negative_functional.spec.ts
https://github.com/danajakulathunga/ITPM-Assignment-01---IT23288430-/blob/main/singlish-playwright/tests/IT23288430_negative_ui.spec.ts
https://github.com/danajakulathunga/ITPM-Assignment-01---IT23288430-/blob/main/singlish-playwright/tests/IT23288430_positive_functional.spec.ts
https://github.com/danajakulathunga/ITPM-Assignment-01---IT23288430-/blob/main/singlish-playwright/tests/IT23288430_positive_ui.spec.ts

Test Coverage
10 Negative functional test cases
3 Positive UI-related test cases (real-time output)
24 Positive functional test cases
03 Negative UI-related test case (real-time output)
