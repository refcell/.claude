Execute safety-validator agent to scan $ARGUMENTS for sensitive secrets and environment variable leaks.

The safety validator will:
1. Scan for hardcoded secrets (API keys, passwords, tokens)
2. Check for exposed environment variables
3. Identify potentially sensitive data in code
4. Review configuration files for security risks
5. Detect common secret patterns and credentials

Report any security vulnerabilities found and suggest remediation.

$ARGUMENTS
