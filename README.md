# Task 4: Secure DevOps - Integrating Security Scanning Tools

## Objective  
Integrate SonarQube or OWASP ZAP into a CI/CD pipeline to identify vulnerabilities during development.

## Tools Used  
- **GitHub Actions** for CI/CD  
- **SonarQube** (initial attempt)  
- **OWASP ZAP** (alternative option)

## What Was Implemented  
- Created a GitHub Action workflow to run SonarQube scans on code commits.  
- Set up environment variables and secrets for secure authentication.  
- Attempted to run SonarQube, but encountered errors (organization key, project binding issues).  
- As an alternative, set up an OWASP ZAP workflow to scan a sample web app.

## Outcome  
The workflows ran, but the security scanning failed due to configuration issues with SonarQube. Despite this, the pipeline setup is in place, and the workflow shows an attempt to perform vulnerability scans.

## Lessons Learned  
- Proper organization and project key configuration is crucial for SonarQube.  
- OWASP ZAP can be a good backup option for dynamic analysis.  
- Debugging CI/CD pipelines requires careful log analysis and trial-and-error.

## Status  
✅ **Pipeline setup complete**  
❌ **Security scan failed (pending fix)**  

## Next Steps  
- Revisit SonarQube configuration or finalize OWASP ZAP integration.  
- Resolve environment and token issues for successful scans.  

