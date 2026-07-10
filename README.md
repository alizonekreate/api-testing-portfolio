# API Testing Portfolio — Alison Kate Lachica

This repository contains API tests I built for the ReqRes API 
(reqres.in) using Postman. Tests run automatically on every push 
using Newman and GitHub Actions.

---

## About This Project

I have a background in full stack web development and I'm now 
building hands-on experience in QA and test automation. This project 
demonstrates my ability to test REST APIs professionally.

---

## API Under Test

**API:** ReqRes — https://reqres.in  
**Type:** REST API  
**Purpose:** Practice API that simulates real user data endpoints  

---

## What I Tested

| Endpoint | Method | Scenario |
|----------|--------|---------|
| /api/users | GET | Get all users |
| /api/users/2 | GET | Get single user |
| /api/users/23 | GET | User not found |
| /api/users | POST | Create user |
| /api/users/2 | PUT | Update user |
| /api/users/2 | DELETE | Delete user |
| /api/login | POST | Login successful |
| /api/login | POST | Login unsuccessful |
| /api/register | POST | Register successful |
| /api/register | POST | Register unsuccessful |

---

## Test Coverage

- Status code validation
- Response body structure checks
- Field existence checks
- Error message validation
- Response time checks

---

## How to Run Locally

Install Newman:
```bash
npm install
```

Run the collection:
```bash
npx newman run postman-collection/reqres-api.json --env-var "api_key=your_api_key_here"
```

---

## CI/CD

Tests run automatically on every push to main via GitHub Actions.

---

## Tools Used

- Postman — collection building and test scripts
- Newman — command line collection runner
- GitHub Actions — CI/CD pipeline
- JavaScript — test assertions

---

## Contact

GitHub: https://github.com/alizonekreate