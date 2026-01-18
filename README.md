# Development
Prompts Development

# ⚡ Prompt Template Playbook 

## 1️⃣ Code Generation Template

### When to Use
- Creating new features
- Writing components
- Writing API routes

### Template

Act as a senior <role> developer.

Task:
<describe exactly what to build>

Tech Stack:
<React / Next.js / Node / Express / MongoDB>

Constraints:

<rule 1>

<rule 2>

<rule 3>

Output:

Return only code

No explanation


### Example

Act as a senior Next.js developer.

Task:
Create a login API route using App Router.

Tech Stack:
Next.js 14, JWT, MongoDB

Constraints:

POST method only

Validate email and password

JSON response only

Output:

Return only code



## 2️⃣ Bug Fixing / Debugging Template

### When to Use
- Runtime errors
- API failures
- Unexpected behavior

### Template
You are a debugging assistant.

Context:
<framework / feature>

Error:
<exact error message>

Code:
<paste only relevant code>

Expectation:

Identify root cause

Suggest exact fix

Output:

Bullet points only

### Example
You are a debugging assistant.

Context:
Next.js App Router API

Error:
Unexpected end of JSON input

Code:
<paste fetch call and API response>

Expectation:

Explain why error occurs

Provide corrected code

Output:

Bullet points only



---

## 3️⃣ Refactoring Template

### When to Use
- Cleaning messy code
- Improving readability
- Simplifying logic

### Template
Refactor the following code.

Goals:

Improve readability

Keep logic same

Constraints:

No new libraries

Same function signature

Output:

Refactored code only

### Example
Refactor the following code.

Goals:

Improve readability

Reduce nested conditions

Constraints:

No new libraries

Same function signature

Output:

Refactored code only


---

## 4️⃣ React / Next.js Component Template

### When to Use
- Forms
- Tables
- Modals
- Dashboard components

### Template
Act as a senior React developer.

Task:
Create a <component name>

Requirements:

Props:

State:

Behavior:

Styling:

Tailwind CSS

Constraints:

Functional component

Reusable

Output:

Code only


### Example
Act as a senior React developer.

Task:
Create a reusable UserTable component

Requirements:

Props: users[]

Pagination support

Row click handler

Styling:

Tailwind CSS

Constraints:

Functional component

Reusable

Output:

Code only


---

## 5️⃣ Backend API Design Template

### When to Use
- CRUD APIs
- Business logic endpoints

### Template
Act as a senior backend developer.

Task:
Design API for <feature>

Requirements:

Endpoint

Request body

Response format

Validation rules

Constraints:

Express.js

MongoDB

Async/await

Output:

Controller code only


### Example
Act as a senior backend developer.

Task:
Design API for creating a customer

Requirements:

POST /api/customers

Validate name and phone

Return created customer

Constraints:

Express.js

MongoDB

Async/await

Output:

Controller code only


---

## 6️⃣ Database Schema Design Template

### When to Use
- Designing MongoDB collections
- Creating Mongoose models

### Template
Act as a database architect.

Task:
Design MongoDB schema for <entity>

Requirements:

Fields with types

Required fields

Index suggestions

Constraints:

Mongoose

Scalable design

Output:

Schema code only


### Example
Act as a database architect.

Task:
Design MongoDB schema for Customer

Requirements:

name (string)

phone (string, unique)

createdAt

Constraints:

Mongoose

Scalable design

Output:

Schema code only


---

## 7️⃣ Security-Critical Template

### When to Use
- Authentication
- RBAC
- Billing
- Payments

### Template
Act as a senior security-focused developer.

Task:
Implement <security feature>

Steps:

Plan solution briefly

Write code

Review for security issues

Constraints:

Follow best practices

Avoid vulnerabilities

Output:

Final code only


### Example
Act as a senior security-focused developer.

Task:
Implement JWT-based authentication for login API

Steps:

Plan solution briefly

Write code

Review for security issues

Constraints:

Follow best practices

Avoid vulnerabilities

Output:

Final code only


---

## 8️⃣ Test Case Generation Template

### When to Use
- Writing unit tests
- Finding edge cases

### Template

Generate test cases for the following logic.

Context:
<feature>

Code:
<paste code>

Requirements:

Positive cases

Negative cases

Edge cases

Output:

Bullet list of test cases


### Example
Generate test cases for the following logic.

Context:
User login API

Code:
<paste login controller>

Requirements:

Valid credentials

Invalid password

User not found

Output:

Bullet list of test cases


---

## 9️⃣ Performance Optimization Template

### When to Use
- Slow APIs
- Heavy React components

### Template
Analyze the following code for performance issues.

Context:
<frontend / backend>

Goals:

Identify bottlenecks

Suggest optimizations

Constraints:

No major refactor

Output:

Bullet points only


### Example
Analyze the following code for performance issues.

Context:
React table with 1,000+ rows

Goals:

Identify bottlenecks

Suggest optimizations

Constraints:

No major refactor

Output:

Bullet points only


---

## 🔟 Planning / Architecture Template

### When to Use
- Starting a new module
- Client requirement planning

### Template
Act as a software architect.

Task:
Plan implementation for <feature>

Include:

High-level flow

Components

Risks

Output:

Short bullet points


### Example
Act as a software architect.

Task:
Plan billing module for Ayurveda shop software

Include:

High-level flow

Components

Risks

Output:

Short bullet points
