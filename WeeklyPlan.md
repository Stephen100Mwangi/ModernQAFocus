## Capstone Project
Build automation for a fictional online reservation/home-buying application.

### Core features:
- User registration
- Login
- Search communities/homes
- Save favorites
- Schedule a tour/reservation
- View reservation history

### Tech Stack:
- C#
- Playwright
- RestSharp
- Azure DevOps
- GitHub
- Allure
- Docker
- SQL

## Month 1: Testing Foundations + Git + Project Setup
### Week 1: Testing Fundamentals
*Learn*
- SDLC
- STLC
- Agile/Scrum
- Shift Left Testing
- Test Pyramid

*Deliverables*
Create notes covering:
- Smoke Testing
- Regression Testing
- Integration Testing
- E2E Testing

*Practical*
Choose your application and identify:
- 10 critical user journeys
- 20 test scenarios

### Week 2: Test Design
*Learn*
- Boundary Value Analysis
- Equivalence Partitioning
- Decision Tables
- State Transitions

*Practical*
For your reservation workflow:

Create
- Positive tests
- Negative tests
- Edge cases

*Deliverable:*
- Test Strategy Document
- Test Cases

### Week 3: Git Deep Dive
*Learn*
```bash
git clone
git branch
git checkout
git merge
git rebase
git stash
```

*Practical*
Create repository: `automation-framework`

*Practice:*
- Feature branches
- Pull requests
- Merge conflicts

### Week 4: C# Refresher
*Learn*
- OOP
- Interfaces
- Collections
- Exception Handling
- LINQ

*Practical*
Create:
- User
- Reservation
- Community


## Month 2: API Testing
### Week 5: Postman Basics
*Learn*
- Collections
- Environments
- Variables

*Practical*
Automate:

```http
POST User
GET User
DELETE User
```

### Week 6: API Assertions
*Learn*

Validate:
- Status Codes
- Headers
- Response Bodies

*Practical*
Create:
`20 API test cases`

### Week 7: RestSharp
*Learn*
- GET
- POST
- PUT
- DELETE

*Practical*
Build API test project:

- Tests
- Services
- Models

### Week 8: API Framework
*Learn*
Framework architecture.

*Practical*
Implement:

- BaseApiClient
- Configuration
- Logging
- Test Data


*Goal:*
One-click execution for all API tests.

## Month 3: Playwright UI Automation
### Week 9: Playwright Installation
*Learn*
- Browsers
- Locators
- Assertions

*Practice*
Automate:
- Login
- Logout

### Week 10: Advanced Locators
*Learn*
```javascript
GetByRole()
GetByTestId()
Locator()
```

*Practice*
Automate:
- Search
- Filter
- Favorite Home

### Week 11: Waits and Stability
*Learn*

Avoid:
```javascript
WaitForTimeout()
```

Use:
```javascript
Expect()
```

*Practice*
Refactor previous tests.

*Goal:*
Zero hard waits.

### Week 12: Page Object Model
*Create*
```text
Pages
 ├─ HomePage
 ├─ LoginPage
 ├─ SearchPage
 └─ ReservationPage
```

*Deliverable*
Framework V1.

## Month 4: Framework Engineering
### Week 13: Framework Structure

*Build:*
```text
AutomationFramework
│
├─ Pages
├─ Tests
├─ API
├─ Utilities
├─ Data
├─ Config
└─ Reports
```

### Week 14: Test Data Management
*Learn*
Generate:
- Users
- Reservations
- Emails

Automatically.

* No hardcoded data.

### Week 15: Configuration Management

*Implement:*
- QA
- UAT
- PROD
environment configs.

### Week 16: Logging & Utilities

*Add:*
- Logs
- Screenshots
- Execution Trace

* Framework should now be production quality.

## Month 5: Reporting + CI/CD
### Week 17: Reporting

*Install:*

- Allure

*Generate:*
- Passed tests
- Failed tests
- Screenshots
- Trends

### Week 18: Advanced Reporting

*Capture:*
- Videos
- Traces
- Network logs

For failed executions.

### Week 19: Azure DevOps Basics
*Learn*
- Repos
- Boards
- Pipelines
- Practical

Push framework to Azure DevOps.

### Week 20: CI Pipeline

*Build pipeline:*
```text
Commit
 ↓
Build
 ↓
Run Tests
 ↓
Publish Report
```

* Pipeline should execute automatically.

## Month 6: Advanced Automation
### Week 21: Docker
*Learn*

- Create:
    Playwright Container
- Run tests inside container.

### Week 22: Parallel Execution

*Enable:*
- 5 Workers
- 10 Workers

Measure execution improvements.

### Week 23: Database Validation
*Learn*

- SQL basics:
```sql
SELECT
JOIN
COUNT
GROUP BY
```

*Practice*

Validate reservation records after automated tests.

### Week 24: Final Project & Portfolio

Build full E2E workflow:
```text
Create User (API)
     ↓
Login (UI)
     ↓
Search Homes
     ↓
Book Reservation
     ↓
Verify DB Record
     ↓
Generate Allure Report
     ↓
Run Through Pipeline
```

## Weekly Study Schedule

- Monday (1 hr)
Theory

- Tuesday (1 hr)
Coding practice

- Wednesday (1 hr)
Coding practice

- Thursday (1 hr)
Framework work

- Friday (1 hr)
Review and refactor

- Saturday (3-4 hrs)
Build project features

- Sunday (2-3 hrs)
Documentation and learning

Total: 10-12 hours/week

## Milestones
- End of Month 1

✅ Understand testing fundamentals
 ✅ Comfortable with Git
 ✅ Project repository ready

- End of Month 2

✅ API automation framework complete

- End of Month 3

✅ Playwright UI automation complete

- End of Month 4

✅ Professional framework architecture

- End of Month 5

✅ CI/CD pipeline running automatically

- End of Month 6

✅ End-to-end automation portfolio project

