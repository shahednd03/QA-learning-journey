# QA-learning-journey
# Week 01 - Manual Testing Fundamentals & Test Case Design

## Key Concepts Covered
- **SDLC & QA Role:** QA involvement starts early in the **Requirements Analysis** phase (Early Testing) to prevent defects before coding begins.
- **Testing Types:**
  - **Smoke Testing:** High-level check on a new build to ensure critical functionalities work without crashing.
  - **Sanity Testing:** Narrow, focused check after a minor bug fix to verify the fix works.
  - **Regression Testing:** Re-testing existing features after code changes to ensure no unintended side effects.
- **Test Design Techniques:** Applied **Equivalence Partitioning (EP)** and **Boundary Value Analysis (BVA)** to optimize test coverage.

## Practical Application (`simple.` E-commerce Demo)
- Designed and executed **10 Manual Test Cases** covering Authentication (Login), Shopping Cart, Search, and Checkout modules.
- **Execution Summary:** 9 Passed, 1 Failed (`TC_08` - Search functionality returned no results for valid keyword `"jacket"`).
