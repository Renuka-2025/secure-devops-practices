# Secure DevOps Practices - Task 4

This repository demonstrates the integration of security scanning tools (SonarQube & OWASP ZAP) in a CI/CD pipeline.  

## Tools Used
- GitHub Actions for automation
- SonarQube for static analysis (attempted, faced configuration issues)
- OWASP ZAP for dynamic analysis (considered as an alternative)

## Challenges Faced
Despite multiple configurations, SonarQube did not successfully analyze the repository due to:
1. **Missing organization key** – Resolved
2. **Pipeline execution failure** – Multiple fixes attempted, but errors persisted.

## Lessons Learned
- Proper integration of security scanning requires **correct authentication tokens**.
- Debugging logs from CI/CD runs are essential for troubleshooting.
- Alternative tools like OWASP ZAP can be explored when one approach fails.

