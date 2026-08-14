# Academybugs Manual Testing Project

Manual testing project for the **Academybugs** shopping application (www.academybugs.com), covering test planning, test case design, execution, and defect reporting.

**Author:** Shaik Chandini
**Date:** 11-May-2026

## About

This project applies manual QA testing practices to a sample e-commerce shopping application, based on user stories across four epics:

- **Epic 1 — Homepage Management:** product display, sorting, filtering, pagination
- **Epic 2 — Product Details:** product info, feedback form, add to cart
- **Epic 3 — Cart Management:** cart totals, quantity updates, checkout, coupons
- **Epic 4 — User Account Management:** signup, login, address management, order history

## Files in this Repository

| File | Description |
|---|---|
| `Academybugs_Test_Plan.docx` | Full test plan — objective, scope, test items, approach, environment, schedule, entry/exit criteria, risks, and roles. |
| `Academybugs_Manual_Testing_Project.xlsx` | Test cases, bug reports, traceability matrix, and test summary (see sheet breakdown below). |

## Workbook Sheet Breakdown

- **Overview** — project snapshot (objective, scope, tools, environment)
- **Test Cases** — 34 detailed test cases with steps, expected/actual results, and pass/fail criteria across all four modules
- **Bug Reports** — defects found during execution, logged in JIRA-style format (summary, severity, type, repro steps, expected/actual)
- **Traceability Matrix** — maps each user story to its test case(s) and execution status
- **Test Summary** — pass/fail counts and defect severity breakdown by module

## Test Approach

- **Levels:** Unit, Integration, System, Regression
- **Types:** Functional, Usability, Exploratory
- **Techniques:** Boundary value analysis, equivalence partitioning, manual exploratory testing
- **Tools referenced:** Zephyr Scale (test case management), JIRA (bug tracking)
- **Environments:** Chrome, Firefox, Safari, Edge — Desktop (Windows, macOS) and Mobile (iOS, Android)

## How to Use

1. Read `Academybugs_Test_Plan.docx` for the overall testing strategy and scope.
2. Open `Academybugs_Manual_Testing_Project.xlsx` to review individual test cases and their results.
3. Cross-check coverage using the **Traceability Matrix** sheet.
4. Review the **Bug Reports** sheet for defects found during execution.
