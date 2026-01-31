# IT23709270-Assignment1
IT23709270 ITPM Assignment 1 - Playwright Automation
Student ID:IT23709270

Automation testing of SwiftTranslator (Singlish to Sinhala) using Playwright.

📂 Folder Structure
text
IT23709270/
├── singlish-playwright/          # Playwright Project
│   ├── tests/                    # Test Scripts
│   ├── package.json
│   └── playwright.config.js
├── IT23709270_TestCases.xlsx     # Test Case Documentation
├── IT23709270_GitHub_Link.txt    # GitHub Repository Link
└── README.md                     # This File
🚀 Quick Start
1. Install & Setup
bash
# Navigate to project
cd IT23709270/singlish-playwright

# Install dependencies
npm install

# Install browsers
npx playwright install
2. Run Tests
bash
# Run all tests
npx playwright test

# View HTML report
npx playwright show-report
3. Run Specific Tests
bash
# Run positive tests
npx playwright test tests/IT23709270_positive_functional.spec.ts

# Run negative tests  
npx playwright test tests/IT23709270_negative_functional.spec.ts

# Run UI tests
npx playwright test tests/IT23709270_positive_ui.spec.ts
📊 Test Coverage
Test Type	Count	File
✅ Positive Functional	24	positive_functional.spec.ts
❌ Negative Functional	10	negative_functional.spec.ts
🖥️ Positive UI	3	positive_ui.spec.ts
⚠️ Negative UI	1	negative_ui.spec.ts
Total: 38 Test Scenarios

🔧 Requirements
Node.js 18+

Visual Studio Code

Git

Microsoft Excel

📋 Test Categories Covered
Sentence structures (Simple/Compound/Complex)

Questions & Commands

Daily language usage

Word combinations

Grammar (Tenses, Negation, Pronouns)

Input length variations

Mixed language content

Punctuation & formatting

Informal language

📈 View Reports
bash
# Generate HTML report
npx playwright show-report

# Generate different formats
npx playwright test --reporter=json
npx playwright test --reporter=junit
⚠️ Important Notes
GitHub repository is public (required for marking)

Excel file has <10% similarity (no plagiarism)

All test cases are original (not from sample)

All files renamed with IT23709270

Submitted before February 1st

Tools & Technologies//

Node.js (v18+ recommended)
Playwright (end-to-end testing framework)
TypeScript (for test development)
JavaScript (for scripting and tests)
XLSX (Excel file generation for test documentation)
@types/node (TypeScript type definitions for Node.js)
HTML Reporter (Playwright built-in)
Modern browsers (Chromium, via Playwright)




