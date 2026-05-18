# Security Skills for AI Agent Vibe Coding

## Purpose

This skill pack forces AI coding agents to treat security as a first-class constraint during implementation, refactor, debugging, and dependency installation.

The agent must not only generate working code. It must also detect common security risks introduced by vibe coding, especially when the user asks for fast implementation.

## Scope

The agent must scan for:

1. Hardcoded secrets
2. SQL injection
3. XSS
4. IDOR / BOLA
5. Slopsquatting / hallucinated packages
6. Brute force
7. Mass assignment
8. Insecure deserialization
9. SSRF
10. Path traversal
11. CSRF
12. Broken access control
13. Weak password hashing
14. JWT none algorithm / weak JWT validation
15. CORS misconfiguration
16. Unrestricted file upload
17. Verbose error messages
18. Missing rate limit
19. Race condition
20. Outdated dependency / known CVE

## Operating Principle

Security review is mandatory when the agent touches:

- authentication
- authorization
- user input
- database query
- file upload/download
- payment/order/wallet/balance logic
- admin endpoint
- environment variables
- dependency installation
- server-side request to external URL
- JWT/session/cookie logic
- CORS/config/deployment files

## Output Rule

Every security-sensitive change must include:

- Risk found
- Why it is dangerous
- Safer implementation
- Test cases or manual verification
- Residual risk if any
