# ⚠️ Edge Case Template

## Overview

This template helps identify and document edge cases that may affect the application's functionality, usability, and stability. It ensures that scenarios beyond the normal user flow are considered during testing.

---

## 📋 Feature Information

| Field | Value |
|--------|-------|
| **Feature** | |
| **Module** | |
| **Prepared By** | |
| **Date** | |

---

## 📝 Description

Provide a brief description of the feature or functionality being tested.

---

## 🔄 Normal Flow

Describe the standard user flow for the feature.

Example:

1. User navigates to the feature.
2. User enters valid information.
3. User submits the request.
4. Operation completes successfully.

---

## ⚠️ Edge Cases

| ID | Scenario | Expected Behaviour | Priority | Status |
|----|----------|-------------------|----------|--------|
| EC-001 | | | High | ☐ |
| EC-002 | | | Medium | ☐ |
| EC-003 | | | Low | ☐ |
| EC-004 | | | Medium | ☐ |

---

## ✍️ Input Validation

Verify the application's behavior for different types of user inputs.

- [ ] Empty Input
- [ ] Null Values
- [ ] Whitespaces Only
- [ ] Special Characters
- [ ] Unicode Characters
- [ ] Minimum Character Limit
- [ ] Maximum Character Limit
- [ ] Invalid Data Format
- [ ] Duplicate Values

---

## 📏 Boundary Value Checks

Verify the application's behavior at the input boundaries.

- [ ] Minimum Allowed Value
- [ ] Maximum Allowed Value
- [ ] Just Below Minimum
- [ ] Just Above Maximum

---

## 👤 User Behaviour

Validate how the application behaves during different user actions.

- [ ] Multiple Clicks
- [ ] Rapid Repeated Actions
- [ ] Browser Refresh
- [ ] Browser Back Button
- [ ] Session Timeout
- [ ] Logout During Operation

---

## 🌐 Environment Scenarios

Validate application behavior under different environmental conditions.

- [ ] Slow Network
- [ ] No Internet Connection
- [ ] Different Browser
- [ ] Different Device
- [ ] Different Screen Resolution

---

## 📌 Test Notes

Document any observations, assumptions, risks, or additional findings during testing.

Example:

- Validation message is inconsistent across browsers.
- Issue occurs only when the network is unstable.
- Application handles duplicate values correctly.

---

## ✅ Review Checklist

Before completing the edge case review, ensure the following have been considered:

- [ ] Input Validation
- [ ] Boundary Value Checks
- [ ] User Behaviour
- [ ] Environment Scenarios
- [ ] Positive Flow Verified
- [ ] Edge Cases Documented
- [ ] Expected Behaviour Defined
