# Test Plan — E-commerce Website

## 1. Purpose
Define the approach for testing the key customer journeys of a sample e-commerce website.

## 2. Objectives
- Verify core shopping workflows behave according to documented requirements.
- Identify functional defects and usability issues.
- Provide traceable test cases and clear execution evidence.

## 3. Scope
### In scope
- Login form validation
- Product listing and product details
- Add, update, and remove cart items
- Cart quantity and price calculations
- Checkout required-field validation
- Order confirmation behavior

### Out of scope
- Real payment transactions
- Production data or customer accounts
- Load, penetration, and full accessibility testing

## 4. Test types
- Functional testing
- Positive and negative testing
- Boundary-value and input-validation testing
- Integration-flow testing
- Regression testing
- Basic usability observations

## 5. Test environment
Fill these details before execution:
- Application/demo URL:
- Build/version:
- Operating system:
- Browser and version:
- Test date:
- Tester:

Use only an application you are authorized to test.

## 6. Entry criteria
- Application is accessible.
- Relevant features are available.
- Test environment and test data are prepared.
- Expected behavior is understood or documented as an assumption.

## 7. Exit criteria
- Planned test cases have an execution status.
- Failed tests have linked defect reports where appropriate.
- Critical workflows have been tested.
- Remaining risks and blocked tests are documented.
- A test summary has been prepared.

## 8. Risks and mitigations
| Risk | Impact | Mitigation |
|---|---|---|
| Requirements are unclear | Expected results may be incorrect | Record assumptions and request clarification |
| Demo environment is unavailable | Tests cannot be completed | Record blocked status and retry later |
| Test data is reused or changes | Results may be inconsistent | Use controlled test data and record setup |
| Third-party payment is unavailable | Checkout may be partially testable | Test validation only; do not make real payments |

## 9. Deliverables
- Test cases (`test-cases.csv`)
- Defect reports (`bug-reports.md`)
- Test summary (`test-summary-report.md`)
- Relevant screenshots or evidence, with sensitive data removed

## 10. Execution status definitions
- **Not Run** — not yet executed
- **Pass** — actual result matches expected result
- **Fail** — actual result differs from expected result
- **Blocked** — execution cannot proceed
- **Not Applicable** — scenario does not apply, with reason recorded

## 11. Approval
Tester:
Reviewer:
Date:
