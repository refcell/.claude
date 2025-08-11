Execute secrets-guardian agent to perform comprehensive secrets detection and environment variable security analysis of $ARGUMENTS.

The secrets guardian will:
1. Scan entire repository for hardcoded secrets and credentials
2. Check git history for previously exposed sensitive data
3. Validate proper environment variable usage and configuration
4. Verify .gitignore properly excludes all sensitive files
5. Detect API keys, tokens, passwords, and private keys
6. Analyze configuration files for security risks
7. Identify high-entropy strings and potential secrets
8. Check for exposed cloud provider credentials
9. Review CI/CD configurations for leaked secrets
10. Provide detailed remediation steps for any findings

Report security vulnerabilities by severity (CRITICAL/HIGH/MEDIUM/LOW) with specific locations and recommended fixes.

$ARGUMENTS