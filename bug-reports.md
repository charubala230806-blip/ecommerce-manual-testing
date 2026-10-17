# Bug Reports — E-commerce Website

> The reports below are **illustrative examples only**, not confirmed defects in a real application. Replace them with issues you personally reproduce, or keep them clearly labelled as practice examples.

## Defect report template

- **Defect ID:** BUG-XXX
- **Title:**
- **Environment:** browser/version, OS, application build
- **Preconditions:**
- **Steps to reproduce:**
  1.
  2.
  3.
- **Expected result:**
- **Actual result:**
- **Severity:** Critical / High / Medium / Low
- **Priority:** P1 / P2 / P3 / P4 (team-defined)
- **Reproducibility:** Always / Intermittent / Once
- **Evidence:** screenshot/video/log filename, with sensitive data removed
- **Related test case:**
- **Status:** New / In Progress / Fixed / Retest / Closed / Reopened

## Practice example 1 — Cart quantity validation

- **Defect ID:** EXAMPLE-BUG-001
- **Title:** Cart accepts a quantity below the allowed minimum
- **Environment:** Practice example; environment not tested
- **Preconditions:** A product is available in the cart.
- **Steps to reproduce:**
  1. Open the cart.
  2. Enter `0` in the quantity field.
  3. Select Update, if available.
- **Expected result:** The application prevents an invalid quantity and displays helpful validation.
- **Actual result:** To be recorded only if reproduced.
- **Severity:** To be assessed after reproduction and impact analysis
- **Priority:** To be agreed with the team
- **Status:** Example only — not a verified defect

## Practice example 2 — Required checkout field

- **Defect ID:** EXAMPLE-BUG-002
- **Title:** Checkout proceeds when a required address field is empty
- **Environment:** Practice example; environment not tested
- **Preconditions:** A product is in the cart and checkout is accessible.
- **Steps to reproduce:**
  1. Navigate to checkout.
  2. Leave a required address field empty.
  3. Submit the form.
- **Expected result:** Checkout is blocked and the missing field is identified.
- **Actual result:** To be recorded only if reproduced.
- **Severity:** To be assessed after reproduction and impact analysis
- **Priority:** To be agreed with the team
- **Status:** Example only — not a verified defect

## Reporting guidelines
- Write titles that describe the observable problem.
- Keep steps numbered, specific, and reproducible.
- Separate expected and actual results.
- Do not guess severity or priority without considering impact and urgency.
- Never include passwords, personal customer information, access tokens, or confidential screenshots.
