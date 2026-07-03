# Future Interns – Cyber Security Task 3

## API Security Risk Analysis Report

This repository contains my Task 3 submission for the Future Interns Cyber Security internship.

### Objective
Conduct a safe, read-only security review of a public demo API and identify common API security risks.

### API Tested
- JSONPlaceholder Public Demo API

### Tool Used
- Postman

### Endpoints Reviewed
- `GET /users`
- `GET /users/1`
- `GET /posts?userId=1`

### Key Findings
- Publicly accessible endpoints
- User information exposed in API responses
- No visible rate limiting
- No authentication required for tested endpoints

### Recommendations
- Implement authentication and authorization controls
- Minimize unnecessary data exposure
- Add rate limiting and monitoring
- Validate inputs and handle errors securely

### Files Included
- API Security Risk Analysis Report PDF
- Postman testing screenshots

## Disclaimer
This work was completed only for educational purposes using a public demo API. All testing used safe, read-only GET requests. No unauthorized access, exploitation, data modification, load testing, or harmful activity was performed.
