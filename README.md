# JSONPlaceholder-API-Testing
📌 A hands-on API testing project using Postman and Newman on JSONPlaceholder's mock API endpoints. Includes automated test scripts, manual test cases, environment configuration, data-driven testing, and command-line execution via Newman.

# Postman API Testing Project

## 📌 Overview
This project contains API test cases written using Postman and executed via Newman (Postman's command-line companion). It includes:
- Positive and negative test cases
- Assertions for status codes, response times, and JSON schema
- Data-driven testing using CSV
- Response time validations
- Schema validations

## 📦 Tools Used
- Postman
- Newman (CLI)
- VS Code (optional)
- Git & GitHub

## 🚀 How to Run
1. Install Newman: `npm install -g newman`
2. Run the collection:
   ```bash
   newman run My_API_Test_Collection.json -d TestData.csv
