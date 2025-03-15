# Troubleshooting Log

## Error 1: SonarQube Authentication Failure
- **Issue:** SONAR_TOKEN was not recognized in GitHub Actions
- **Fix Attempted:** Verified secrets in GitHub, regenerated token
- **Outcome:** Issue resolved

## Error 2: "Could not find default branch for project"
- **Issue:** SonarQube could not detect the project correctly
- **Fix Attempted:** Added organization key `renuka-2025`, updated workflow
- **Outcome:** Still failed

## Final Decision:
After multiple attempts, the pipeline could not successfully integrate SonarQube. The process and learnings are documented for future improvements.
