# User Stories

## 1. Create Account / Product

**As a** customer
**I need** to be able to create a new account
**So that** I can use the service and save my details

### Details and Assumptions
- The user provides name, email, and address
- Email must be unique
- Data is stored in the database via the REST API

### Acceptance Criteria
```gherkin
Given the service is running
When I POST a new account with valid data
Then I should get a 201 Created response with the new account ID
