# 🔐 CRM Platform – User Authentication Test Cases

This repository contains detailed manual test cases for the **User Authentication and Login** flows of a CRM system. These cases cover both positive and negative validation scenarios to ensure secure and user-friendly access.

---

## 🧪 Covered Modules

### 1️⃣ CRM User Validation
- Validate required fields (email, company ID, password)
- Client-side and server-side error handling
- Error message accuracy and consistency
- Session management checks (auto logout, multi-login prevention)

### 2️⃣ Login with Company ID (Test Case TC2)
- Login using valid Company ID and Password
- Case sensitivity validation
- Redirection to dashboard upon successful login
- Access restrictions based on roles after login

### 3️⃣ Login with Email & Password (Test Case TC3)
- Valid login via email + password
- Forgot password flow validation
- Remember me checkbox behavior
- Browser compatibility checks (Chrome, Firefox, Edge)

### 4️⃣ Negative Input – Login Using Invalid Company ID
- Attempt login with wrong/inactive Company ID
- Validation for blank inputs
- Error message display and timeout behavior
- Rate-limiting and brute-force prevention (if implemented)

### 5️⃣ User Login & Registration
- New user registration with valid/invalid data
- Field-level validations (email format, password strength, terms checkbox)
- Success & failure states
- Email/OTP verification (if applicable)
- Post-registration auto-login behavior

---

## 📝 Test Case Structure

Each test case includes:
- Test Case ID (e.g., TC2, TC3)
- Module
- Test Title
- Preconditions
- Steps to Execute
- Expected Result
- Actual Result
- Status (Pass/Fail)
- Notes / Screenshots

---

## 🔧 Tools Used

- Manual Testing  
- Test Design in Excel/Markdown  
- API Validation (Login/Registration) using Postman  
- Test Data Management  
- Defect Reporting via GitLab/Trello

---

## 🧑‍💻 Who This is For

- QA Engineers testing CRM platforms  
- Dev teams verifying backend login flows  
- Security testers reviewing auth mechanisms  
- UAT testers during CRM release cycles

---

## 📩 Contact

Need help or want to collaborate?  
📧 svshinde.work@gmail.com

---

> “Secure, smooth, and tested logins—because the user journey begins with a click.” 🔐
