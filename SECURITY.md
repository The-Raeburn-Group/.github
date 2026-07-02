# Security Policy

Raeburn AI takes security seriously.

These projects may involve AI agents, external tools, business data, documents, credentials, APIs, and workflow automation. Security, privacy, and safe deployment are core design requirements.

## Reporting a Vulnerability

Please do not open a public GitHub issue for security vulnerabilities.

Instead, report the issue privately through GitHub's private vulnerability reporting if enabled, or contact the project maintainer through the official Raeburn Group channels.

Please include:

- Repository name
- Affected component
- Vulnerability summary
- Steps to reproduce
- Potential impact
- Suggested remediation, if known

## Scope

Security issues may include:

- Authentication or authorisation bypass
- Secret leakage
- Unsafe agent/tool execution
- Prompt injection vulnerabilities
- Insecure MCP connector behaviour
- Data exposure
- Cross-tenant access issues
- Unsafe file handling
- Supply-chain risks
- Insecure defaults

## Security Principles

Raeburn AI projects should follow:

- Least privilege access
- Explicit human approval for high-risk actions
- Secrets never committed to source control
- Audit logging for sensitive operations
- Clear trust boundaries for tools and connectors
- Safe defaults for production deployment
- Dependency review and regular updates

## Supported Versions

Projects under active development are supported on the default branch unless otherwise stated in the repository README.

## Responsible Disclosure

We aim to acknowledge valid reports quickly and resolve confirmed vulnerabilities as soon as practical.
