ID: BUG-001

Title: Inconsistent Button Scaling in Guest Login Pop-up

Severity: Low (UI/UX Inconsistency)

Description: When the Guest Login modal is triggered, the "Sign Up" button does not match the dimensions of the "Submit" button, creating a broken visual hierarchy.

Steps to Reproduce:

Navigate to https://aflon.edu.ng/

Click on the "Guest Login" button.

Observe the "Sign Up" and "Submit" buttons in the pop-up.

Expected Result: Both buttons should have uniform padding and height.

Actual Result: "Sign Up" button is extra-large compared to "Submit."


ID: BUG-002

Title: Mobile Centering

Device Tested: iPhone 13 (Simulated) / Android Chrome.

Issue: Burger menu elements are offset from the center, leading to a "cut-off" appearance on screens smaller than 375px.

Technical Suggestion: The container likely lacks justify-content: center or has a fixed width that exceeds the viewport width.
