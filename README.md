# User Management API Testing using Postman Collection Runner

## 📌 Project Overview

This project demonstrates **API Functional Testing** for a **User Management REST API** using **Postman Collection Runner**. The collection automates end-to-end testing of CRUD (Create, Read, Update, Delete) operations with request chaining, response validation, authentication, and basic security checks.

The objective is to validate the API's functionality, reliability, and data integrity through automated execution and assertions.

---

## 👩‍💻 Project Information

| Field | Details |
|--------|---------|
| **Project Name** | User Management API |
| **Testing Type** | API Functional Testing |
| **Tool** | Postman |
| **Execution** | Postman Collection Runner |
| **API Module** | User CRUD Operations |
| **Prepared By** | Deepa Girish Patil |
| **Version** | 1.0 |

---

# 🎯 Objectives

This project validates the following API functionalities:

- ✅ User Creation
- ✅ User Retrieval
- ✅ User Update
- ✅ User Deletion
- ✅ Token-Based Authentication
- ✅ SQL Injection Testing
- ✅ Response Validation
- ✅ Data Integrity Verification
- ✅ Automated Request Chaining

---

# 🚀 Features

- Complete CRUD API testing
- Automated execution using Postman Collection Runner
- Positive and negative test scenarios
- Request chaining using environment variables
- Automated assertions for status codes and responses
- Authentication validation
- SQL Injection test cases
- Response time validation
- Duplicate data validation
- Basic concurrency testing
- Regression testing support

---

# 📂 Project Structure

```
User-Management-API/
│
├── Postman Collection/
│   └── UserManagement.postman_collection.json
│
├── Environment/
│   └── QA.postman_environment.json
│
├── Test Plan/
│   └── API_Test_Plan.pdf
│
├── Screenshots/
│
└── README.md
```

---

# 🛠️ Technology Stack

- Postman
- REST API
- JSON
- HTTP Methods
- Postman Collection Runner

---

# 🔐 Authentication

The API uses **Token-Based Authentication**.

The collection automatically includes the authentication token for secured API requests.

---

# 📌 Test Coverage

## ✅ Create User API

- Create user with valid data
- Mandatory field validation
- Missing request body
- Invalid JSON body
- Null field validation
- Special character validation
- Multiple user creation
- Unique ID validation

---

## ✅ Read User API

- Retrieve all users
- Retrieve user by valid ID
- Retrieve user by invalid ID
- Verify returned user data
- Verify response data types

---

## ✅ Update User API

- Update existing user
- Update invalid user
- Update non-existing user
- Missing request body
- Field validation
- Verify updated values

---

## ✅ Delete User API

- Delete existing user
- Delete invalid user
- Repeated delete validation
- Verify deleted user cannot be accessed

---

## ✅ Validation Testing

- HTTP Status Codes
- Response Body Validation
- Mandatory Fields
- Response Schema Validation
- Response Headers

---

## ✅ Security Testing

- Unauthorized Access
- Invalid Authentication Token
- SQL Injection Validation
- Data Leakage Validation

---

## ✅ Performance Testing

- Response Time Validation
- Multiple Iteration Execution
- Collection Runner Execution

---

## ✅ Data Integrity Testing

- Unique User ID Validation
- Duplicate Data Validation
- Data Persistence Validation

---

## ✅ Concurrency Testing

- Simultaneous Update Handling
- Multiple User Operations

---

# ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/User-Management-API.git
```

### 2. Open Postman

Import the following files:

- UserManagement.postman_collection.json
- QA.postman_environment.json

### 3. Configure Environment

Update:

- Base URL
- Authentication Token (if required)

### 4. Run Collection

Open **Collection Runner**

Select:

- Collection
- Environment
- Number of Iterations

Click **Run**.

---

# 📊 Test Scenarios Covered

| Module | Test Scenarios |
|----------|----------------|
| Create | Valid creation, Invalid body, Missing body, Mandatory fields, Special characters |
| Read | Existing user, Invalid ID, Data verification, Data type validation |
| Update | Valid update, Invalid ID, Non-existing user, Missing body |
| Delete | Successful delete, Repeated delete |
| Validation | Status codes, Schema validation, Mandatory fields |
| Security | Authentication, SQL Injection, Unauthorized access |
| Performance | Response time validation |
| Concurrency | Simultaneous updates |

---

# ✅ Entry Criteria

Testing begins when:

- QA environment is available
- Authentication credentials are provided
- Test data is ready

---

# ✅ Exit Criteria

Testing is completed when:

- All critical test cases pass
- Regression testing is completed
- Postman collection is committed to GitHub

---

# 🐞 Defect Management

Each defect includes:

- Defect ID
- API Name
- Request Payload
- Response Payload
- Expected Result
- Actual Result
- Severity
- Priority

---

# ⚠️ Risks & Mitigation

| Risk | Mitigation |
|------|------------|
| Test Data Collision | Generate unique test data |
| Token Expiration | Refresh authentication token before execution |

---

# 📦 Deliverables

- Postman Collection (.json)
- API Test Plan
- GitHub Documentation
- Test Execution Results

---

# 🎯 Automation Success Criteria

Automation is considered successful when:

- All test scripts pass
- Expected HTTP status codes are returned
- No duplicate user IDs are created
- No data leakage occurs across iterations
- Response times remain within acceptable limits

---

# 📈 Skills Demonstrated

This project showcases practical experience in:

- REST API Testing
- Postman Collection Runner
- CRUD API Validation
- API Automation
- Request Chaining
- Environment Variables
- JSON Validation
- HTTP Methods (GET, POST, PUT, DELETE)
- Authentication Testing
- SQL Injection Testing
- Response Validation
- Data Integrity Testing
- Performance Validation
- Regression Testing
- Functional Testing
- Negative Testing

---

# 📷 Sample Execution

After running the collection, Postman provides:

- Total Requests Executed
- Passed Assertions
- Failed Assertions
- Execution Time
- Response Time Metrics

---

# 🤝 Author

**Deepa Girish Patil**

**QA Automation Engineer | API Testing | Postman | Manual Testing**

---

## ⭐ Support

If you found this project useful, consider giving the repository a **Star ⭐** to support the project.
