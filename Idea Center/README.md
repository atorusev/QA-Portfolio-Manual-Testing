# Idea Center Web Application

## Project Overview
The **Idea Center** web application is designed to facilitate idea sharing and management. The goal of this project was to evaluate the application's functionality, document test cases, identify bugs, and perform API testing.

---

## Key Functionalities Tested
1. **User Registration**:
   - Signing up using username, email, and password with field validations.
   - Alternative sign-up options via Google and Facebook.

2. **User Login**:
   - Logging in with registered credentials.
   - Remember password functionality.

3. **Profile Management**:
   - Viewing and editing profile information, including profile picture, name, and personal details.

4. **Idea Management**:
   - Creating, editing, and deleting ideas.
   - Searching for ideas using keywords.

5. **API Endpoints Tested**:
   - User creation (`POST /api/User/Create`)
   - User authentication (`POST /api/User/Authentication`)
   - Idea creation (`POST /api/Idea/Create`)
   - Listing all ideas (`GET /api/Idea/All`)
   - Editing an idea (`PUT /api/Idea/Edit`)
   - Deleting an idea (`DELETE /api/Idea/Delete`)

---

## Testing Artifacts
1. **Test Cases**:
   - Comprehensive test cases were created for each feature, including edge cases and negative scenarios.

2. **Bug Reports**:
   - Documented bugs with detailed reproduction steps, expected vs. actual results, and severity levels.

3. **API Testing**:
   - Postman collection containing requests for key API endpoints.

---

## Tools Used
- **Excel**: To document test cases and bug reports.
- **Postman**: For API testing and creating a structured collection of requests.

---

## Summary of Work
- **Number of Test Cases**: 15+ covering all functionalities.
- **Number of Bugs Found**: 5+ critical bugs identified and documented.
- **Deliverables**:
  - Test case documentation (`.xlsx` file).
  - Postman collection (`.json` file).
