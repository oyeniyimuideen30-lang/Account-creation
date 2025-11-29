# Account Creation API – Postman Collection

This repository contains a Postman Collection that showcases a complete flow for user account creation, authentication, and verification.  
It is designed as part of my API testing and backend integration portfolio to demonstrate my ability to work with real-world API endpoints, validate responses, and structure test workflows in Postman.

---

## 📌 About the Collection
The collection provides a set of API requests commonly used in modern fintech or user onboarding systems.  
It includes sample payloads, test scripts, and structured endpoints to help clients or reviewers understand my approach to:

- API testing  
- Request/response validation  
- User authentication flows  
- Identity verification  
- Error handling and workflow documentation  

---

## 📁 Endpoints Included

### 1. **Login**
`POST /auth/login`  
Authenticates a user with login credentials and device information.

### 2. **Register User**
`POST /auth/register`  
Creates a new user account with full personal details (email, phone, BVN, DOB, address, etc.).

### 3. **BVN Verification**
`POST /auth/bvn/verify`  
Validates a user’s BVN before account creation.

### 4. **NIN Face Verification**
`POST /nin-verification/verify-with-face`  
Matches the user’s NIN to a facial image URL for identity confirmation.

### 5. **Get Account Details**
`GET /api/v1/accounts/user/{id}/details`  
Fetches full account information for a registered user.

### 6. **Logout**
`POST /auth/logout`  
Logs out a user and invalidates their token.

### 7. **Delete Account**
`DELETE /auth/delete`  
Deletes a user account using a provided user ID.

---

## 🔧 Environment Variable

The collection uses one environment variable:

| Variable | Description |
|----------|-------------|
| `{{base URL}}` | The root domain of the API you want to test |

Be sure to set this in your Postman environment before running requests.

---

## 🚀 How to Use

1. Download the `Account creation.postman_collection.json` file.  
2. Open **Postman** → Click **Import** → Select the file.  
3. Set the **base URL** value in your Postman environment.  
4. Run or modify the requests as needed.

---

## 🎯 Purpose of This Repository

This repository is part of my development and QA portfolio.  
It demonstrates my ability to:

- Structure API collections professionally  
- Test and document backend endpoints  
- Work with authentication systems  
- Validate identity verification workflows  
- Provide clean and understandable technical documentation  

If you are a potential client looking to collaborate on API development, backend systems, QA testing, or Postman workflow automation, this repo serves as a practical demonstration of my skill set.

---

## 📬 Contact

For collaborations, hiring or projects:  
**Email:** oyeniyimuideen30@gmail.com 
**LinkedIn/GitHub: https://www.linkedin.com/in/muideen-oyeniyi-93a640368

---

Thank you for viewing this project!
