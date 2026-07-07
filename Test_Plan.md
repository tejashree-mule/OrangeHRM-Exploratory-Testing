# Test Plan

## Project Information

| Item | Details |
|------|---------|
| Project | OrangeHRM Demo |
| Module | Login |
| Tester | Tejashree Mule |
| Testing Type | Exploratory Testing |
| Environment | Windows 11 |
| Browser | Google Chrome (Latest) |
| Date | July 2026 |

---

# Objective

To verify the Login functionality of the OrangeHRM Demo application by performing exploratory testing, functional validation, UI checks, and input validation.

---

# Scope

### In Scope

- Login Page
- Username Field
- Password Field
- Login Button
- Forgot Password
- Logout Functionality
- Validation Messages

### Out of Scope

- Employee Management
- Recruitment
- Leave Module
- Dashboard Features
- Performance Module

---

# Testing Approach

The Login module will be tested using exploratory testing techniques.

Testing will include:

- Functional Testing
- Negative Testing
- Boundary Value Testing
- Input Validation
- UI Verification
- Basic Accessibility Checks

---

# Test Environment

| Component | Details |
|-----------|----------|
| OS | Windows 11 |
| Browser | Google Chrome |
| URL | https://opensource-demo.orangehrmlive.com/ |
| Username | Admin |
| Password | admin123 |

---

# Entry Criteria

- Application is accessible.
- Valid login credentials are available.
- Browser is installed.
- Internet connection is stable.

---

# Exit Criteria

Testing is considered complete when:

- All planned test scenarios have been executed.
- Observations are documented.
- Bug reports (if any) are created.
- Test Summary Report is completed.

---

# Deliverables

- Test Plan
- Test Scenarios
- Bug Report
- Screenshots
- Test Summary Report

---

# Risks

- Demo environment may change without notice.
- Internet connectivity issues.
- Test data may be reset by the application.

---

# Assumptions

- Demo credentials remain valid.
- Application is available during testing.
- No backend/database access is available.

---

# Success Criteria

The Login functionality should:

- Allow valid users to log in successfully.
- Reject invalid credentials.
- Display meaningful validation messages.
- Protect password input.
- Redirect authenticated users to the Dashboard.
