API Security Risk Analysis

This project demonstrates a read-only API security assessment performed on a public test API, simulating how cybersecurity professionals evaluate SaaS platforms for security risks.

🎯 Objective
Analyze API endpoints
Identify common security vulnerabilities
Assess authentication and access control
Map risks to industry standards
Provide remediation recommendations
🌐 API Tested
JSONPlaceholder

Base URL:
https://jsonplaceholder.typicode.com

🛠️ Tools Used
Insomnia

🔍 Key Findings
🔴 No authentication required
🔴 Broken authorization (access to other users’ data)
🟠 Excessive data exposure
🟠 No rate limiting
🟡 Missing security headers
🟡 Input validation issues
🔐 OWASP API Top 10 Mapping

Findings align with the OWASP API Security Top 10:

API1: Broken Object Level Authorization
API2: Broken Authentication
API3: Excessive Data Exposure
API4: Lack of Rate Limiting
API8: Security Misconfiguration
API10: Input Validation Issues

💼 Business Impact
If present in real systems, these issues could lead to:

Data breaches
Unauthorized access
Compliance violations (e.g., POPIA)
Service abuse or downtime
✅ Recommendations
Implement authentication (OAuth2, JWT)
Enforce role-based access control (RBAC)
Apply rate limiting
Minimize exposed data
Validate all inputs
📌 Disclaimer

This assessment was conducted on a public demo API for educational purposes only.
No exploitation or harmful testing was performed.

🚀 Author
Mokoena Lebohang Solomon
Aspiring Cybersecurity / AppSec Analyst
