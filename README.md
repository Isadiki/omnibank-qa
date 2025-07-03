# 🧪 OmniBank QA Testing Project

Comprehensive QA project covering **web & mobile testing**, using:
- ✅ Manual test artifacts
- 🔁 Automation with **Selenium (Java)** and **Cypress**
- 📬 API testing via **Postman**
- 🔐 Security & risk via **BORT testing**

---

## 🔧 Tools & Technologies

- Java, Selenium, Maven, TestNG
- Cypress for UI testing
- Postman for API collections
- JIRA, Octane (ALM), Excel
- Manual & exploratory testing practices

---

## 📁 Project Structure

```bash
omnibank-qa/
├── manual/
│   ├── test-plan.pdf
│   ├── test-cases.xlsx
│   └── defect-log.xlsx
├── automation/
│   └── src/test/java/...
├── cypress/
│   └── e2e-tests/
├── api/
│   ├── Postman_Collection.json
│   └── API-Test-Summary.md
└── bort-testing/
    └── BORT_Testing_Strategy.pdf
✅ Manual QA Artifacts
Test Plan: Scope, objectives, environments

Test Cases: Functional, UI, and regression

Defect Log: Prioritized with severity & status

🤖 Automation Highlights
🔹 Selenium Java
Login & registration flows

Assertions on transaction history

Configured using Maven + TestNG

🔸 Cypress
Web UI test: account summary

Mobile view testing via viewport simulation

📬 API Testing
Auth, Transactions, User profile

Assertions using Postman pre-request/test scripts

Collection + test summary included

🔐 BORT Testing Strategy
Covers:

Broken Access Control

Injection vulnerabilities

Authentication flaws

Logging/monitoring strategies

📸 Screenshots (Add Your Own)
Placeholder for test dashboard/report screenshots

🏁 How to Run Automation Locally
bash
Copy
Edit
# Selenium
mvn clean test

# Cypress
npx cypress open
🙋‍♀️ Author
Ivy Sadiki
Senior Test Analyst | QA Leader | Automation & Data QA
