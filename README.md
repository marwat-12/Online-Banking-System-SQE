# Online Banking System – Software Quality Engineering (SQE)

## Project Overview

This project focuses on Software Quality Engineering (SQE) for an Online Banking System. It demonstrates how software quality can be evaluated and improved through systematic testing techniques, quality requirements, test case design, and automated testing.

The project covers different software testing methodologies to verify the functionality, reliability, security, performance, and overall quality of an online banking application.

## Project Features

- System Analysis and Quality Requirements
- Functional and Non-Functional Requirements
- Quality Attributes Analysis
- Equivalence Partitioning
- Boundary Value Analysis
- State Transition Testing
- White Box Testing and Control Flow Analysis
- 100% Branch Coverage Test Cases
- Data Flow Testing
- V-Model Implementation
- Agile Testing Framework
- Regression Testing Strategy
- Performance Testing
- Security Testing
- Selenium WebDriver Automation

## Technologies and Tools

- **Programming Language:** Python 3.14
- **Automation Tool:** Selenium WebDriver 4.x
- **Testing Framework:** Pytest 9.0
- **Browser:** Google Chrome
- **HTML Reporting:** Pytest-HTML
- **Parallel Testing:** Pytest-xdist
- **Driver Management:** WebDriver Manager

## Testing Environment

The project uses the Parabank demo application as its target testing environment.

**Application:** https://parabank.parasoft.com/parabank

## Installation

Install the required Python libraries:

```bash
pip install selenium pytest webdriver-manager pytest-html pytest-xdist
```

## Running Automated Tests

Execute the automated test suite using:

```bash
python -m pytest test_banking_system.py -v -s --html=report.html
```

To execute tests using parallel browser instances:

```bash
python -m pytest test_banking_system.py -v -s -n 10 --html=report.html
```

## Automated Test Coverage

The automation suite contains five major testing classes:

| Test Class | Testing Area |
|---|---|
| TestLogin | Authentication |
| TestFundTransfer | Fund Transfers |
| TestAccountFeatures | Balance and Transaction History |
| TestAdminReports | Admin Panel |
| TestSecurityBasic | Security Testing |

## Project Objectives

The main objective is to demonstrate the practical implementation of Software Quality Engineering concepts through a banking application. The project combines manual testing techniques, structural testing, testing models, and Selenium-based automation to improve software reliability and identify potential defects.

## Project Information

- **Course:** Software Quality Engineering
- **Course Code:** SEC321
- **University:** Iqra University, Islamabad
- **Year:** 2026


---

*This repository contains the Software Quality Engineering project documentation and associated Python automation testing files.*
