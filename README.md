
## JSONPlaceholder API – Postman Automation Portfolio Project

This project showcases API testing using Postman, focusing on dynamic request chaining, variable management, data-driven testing, and HTML reporting with Newman.

---

## Project Overview

This test suite is designed to automate key API operations on the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) fake REST API. It includes:

- Complete CRUD operations for `/posts` and `/comments` endpoints
- Dynamic chaining using environment variables (e.g., PostId,UserId)
- Data-driven testing using CSV input with Collection Runner
- Validation scripts for status codes, response time, data types, and content
- Newman CLI execution + detailed HTML reports

---

##  Features

-  Tokenless REST API for clean testing logic
-  Chaining: POST → GET → PATCH → DELETE with dynamic IDs
-  Parameterization: Run with CSV file using Collection Runner
-  Loops for validating array body responses
- Assertions:
  - Status code
  - Content-Type
  - Response time
  - Response size
  - Field data types
  - Field value matches

---

## Tools Used

| Tool        | Purpose                      |
|-------------|------------------------------|
| Postman     | Manual API testing, scripting |
| JavaScript  | Pre-request + test scripts    |
| Newman CLI  | Command-line automation       |
| htmlextra   | Fancy HTML reporting          |
| CSV         | Data-driven testing           |

---

##  How to Run

###  Using Postman Collection Runner
1. Import the collection and environment files
2. Click "Runner"
3. Select the collection, environment, and CSV file
4. Run all iterations and view logs + test results

---

##  Sample Report Screenshot

> You can embed an HTML report screenshot here for GitHub

---

##  Author

**Ranum Khan**  
[LinkedIn](https://linkedin.com/in/ranum-khan-qaengineer) | [GitHub](https://github.com/Ranumkhan123)  
Experienced QA Engineer with a strong foundation in manual and API testing, building automation-ready Postman collections and rich documentation.

---

##  License

This project uses public APIs and is intended for educational and portfolio purposes only.
