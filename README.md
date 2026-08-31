# QA Cypress Tests – Mini Project Automation

This repository contains a **Cypress** end-to-end test for a practice automation website.

The test interacts with various form controls and elements on the page.

## Test Coverage

The test (`maryqaassignment.cy.js`) performs the following actions:

- Visits the practice website
- Fills out a form with:
  - Name
  - Email
  - Phone number
  - Address (textarea)
- Selects a country from a dropdown
- Checks and unchecks checkboxes (Monday & Sunday)
- Selects a radio button (Female)
- Uploads a mock PDF file
- Scrolls to the footer
- Verifies the page title

## Tech Stack

- **Cypress**
- **JavaScript**

## Website Under Test

🔗 [https://testautomationpractice.blogspot.com](https://testautomationpractice.blogspot.com)

## Getting Started

### Prerequisites

- Node.js installed
- Cypress installed

### Installation

```bash
# Clone the repository
git clone https://github.com/marymachariam/QA-Cypress-Tests.git
cd QA-Cypress-Tests
```
## Running the Test
``` bash
# Open Cypress Test Runner
npx cypress open

# Or run in headless mode
npx cypress run
```
## Project Structure
``` bash
QA-Cypress-Tests/
├── maryqaassignment.cy.js
└── README.md
```
## Author
Mary Macharia

# Install dependencies
npm install
