# 🔒 Security Policy

## 🛡️ Supported Versions

We actively support and provide security updates for the following versions of Dragon's Dogma II Offline Setup Assistant:

| Version | Supported | Security Updates |
| ------- | --------- | ---------------- |
| 2.1.x   | ✅ Yes    | Full support     |
| 2.0.x   | ✅ Yes    | Critical only    |
| 1.9.x   | ⚠️ Limited | Critical only   |
| 1.8.x   | ❌ No     | End of life     |
| < 1.8   | ❌ No     | End of life     |

## 🚨 Reporting Security Vulnerabilities

### What Qualifies as a Security Issue?

**Gaming-Specific Security Concerns:**
- Save file corruption or manipulation vulnerabilities
- Unauthorized access to game installation directories
- Configuration file injection attacks
- Memory manipulation exploits
- Network-based attacks on offline components

**General Security Issues:**
- Code execution vulnerabilities
- Privilege escalation
- Data exposure or leaks
- Authentication bypasses
- Input validation flaws

### How to Report

**For Critical Vulnerabilities:**
1. **DO NOT** create a public GitHub issue
2. Email us directly at: `security@dragons-dogma-ii-offline.github.io`
3. Include detailed information about the vulnerability
4. Provide steps to reproduce if possible

**For Non-Critical Issues:**
- Create a private security advisory on GitHub
- Use our security issue template
- Tag with appropriate severity level

### What to Include in Your Report

```
Vulnerability Type: [Code Execution/Data Exposure/etc.]
Affected Component: [Setup Assistant/Config Tool/etc.]
Game Version Compatibility: [All/Specific versions]
Operating System: [Windows/Linux/macOS]
Severity Assessment: [Critical/High/Medium/Low]

Description:
[Detailed description of the vulnerability]

Steps to Reproduce:
1. [Step one]
2. [Step two]
3. [Step three]

Expected Behavior:
[What should happen]

Actual Behavior:
[What actually happens - security impact]

Potential Impact:
[Save corruption/System compromise/Data exposure/etc.]

Suggested Fix:
[If you have suggestions for mitigation]
```

## ⏱️ Response Timeline

| Severity | Initial Response | Investigation | Fix Release |
|----------|------------------|---------------|-------------|
| Critical | 24 hours        | 72 hours      | 7 days      |
| High     | 48 hours        | 5 days        | 14 days     |
| Medium   | 5 days          | 14 days       | 30 days     |
| Low      | 7 days          | 21 days       | Next release|

## 🎮 Gaming-Specific Security Measures

### Save File Protection
- All operations are sandboxed to prevent save corruption
- Automatic backup creation before major configuration changes
- Integrity checks for modified game files
- Rollback mechanisms for failed operations

### Installation Security
- Verification of game installation paths
- Protection against directory traversal attacks
- Validation of configuration file formats
- Safe handling of game binary modifications

### Offline Operations
- No network connections for core functionality
- Local-only configuration storage
- Encrypted sensitive settings
- Secure temporary file handling

## 🔐 Security Best Practices for Users

### Installation Safety
- Download only from official sources
- Verify file checksums before installation
- Use dedicated game directories
- Regular backup of game saves and configurations

### Configuration Security
- Review configuration changes before applying
- Use separate profiles for experimental settings
- Monitor game behavior after modifications
- Keep original game files as backup

### System Protection
- Run with minimal required privileges
- Use updated antivirus software
- Monitor system for unusual behavior
- Regular security updates for OS and dependencies

## 🛠️ Security Development Process

### Code Review Requirements
- All code changes require security review
- Automated security scanning in CI/CD
- Regular dependency vulnerability audits
- Penetration testing for major releases

### Third-Party Dependencies
- Regular updates for security patches
- Vulnerability scanning of all dependencies
- Minimal dependency principle
- Vendor security assessment

## 📋 Security Checklist for Developers

**Before Each Release:**
- [ ] Static code analysis completed
- [ ] Dependency vulnerabilities checked
- [ ] Security test suite passed
- [ ] Code review with security focus
- [ ] Documentation updated for security features

**For Major Features:**
- [ ] Threat modeling completed
- [ ] Security architecture review
- [ ] Penetration testing conducted
- [ ] Security documentation updated

## 🎖️ Security Hall of Fame

We recognize security researchers who help improve our project:

| Researcher | Vulnerability Type | Severity | Date |
|------------|-------------------|----------|------|
| [Name]     | [Type]            | [Level]  | [Date] |

*Want to be listed here? Report a valid security vulnerability!*

## 📞 Contact Information

- **Security Email**: security@dragons-dogma-ii-offline.github.io
- **General Contact**: support@dragons-dogma-ii-offline.github.io
- **Emergency**: Use GitHub security advisories for urgent issues

## 📚 Additional Resources

- [OWASP Gaming Security Guide](https://owasp.org/www-project-game-security-framework/)
- [Secure Gaming Development Practices](https://github.com/Dragon-s-Dogma-II-Offline/dragons-dogma-2-offline-setup-assistant/wiki/Security)
- [Our Security Architecture Documentation](docs/security-architecture.md)

---

**Protecting gamers and their data is our top priority! 🛡️🎮** 