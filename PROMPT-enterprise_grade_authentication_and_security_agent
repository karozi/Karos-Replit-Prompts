🛡️ **Prompt: Implement Enterprise-Grade Authentication & Security for a Web or API-Based Application**

You are a **senior security engineer** or **backend architect** tasked with designing and implementing a **comprehensive, enterprise-grade security layer** for a backend application.

---

### 🎯 Application Context
Please apply this security system to the following application type:  
**[insert application type, e.g., “HIPAA-compliant telehealth platform,” “B2B SaaS CRM,” or “GDPR-aligned e-commerce API”]**

Specify the relevant compliance requirement:  
**[select one or more: GDPR / HIPAA / SOC2 / FedRAMP / PCI-DSS]**

---

### 🔐 Authentication & Access Control
Implement and justify your choices for:
1. **JWT and/or OAuth2** authentication setup (include token lifespan, refresh logic).
2. **Multi-Factor Authentication (MFA)** – via email, authenticator app, or SMS.
3. **Role-Based Access Control (RBAC)** – with support for multiple roles and permissions.
4. **Password policies** – enforce complexity, rotation, expiration, and history rules.
5. **Session management** – invalidate tokens on logout, detect session reuse or hijacking.

---

### 🛡️ Application Security Hardening
Configure and apply the following protections:
6. **CORS policies** – restrictive origin + method/headers definition.
7. **Rate limiting** – adjustable per endpoint and IP/user level.
8. **Input sanitization** – against script injection, malformed payloads, etc.
9. **SQL injection prevention** – via prepared statements, ORM security practices.
10. **XSS protection** – output encoding, content-type headers, CSP setup.
11. **CSRF protection** – CSRF tokens, double-submit cookie, or SameSite.
12. **Security headers** – apply `Strict-Transport-Security`, `X-Frame-Options`, `X-Content-Type-Options`, and `Content-Security-Policy`.

---

### 🧾 Logging & Auditability
13. Implement a **structured audit logging system**:
    - Log auth attempts, data access events, role changes, and failures.
    - Ensure logs are immutable, timestamped, and traceable.
14. Ensure logs meet **compliance requirements** (e.g., HIPAA audit trail, SOC2 retention policy).

---

### ✅ Compliance Mapping
15. Map your implementation to your chosen compliance framework:
    - E.g., for GDPR: include consent flow, data deletion audit, user data access.
    - For HIPAA: include PHI access traceability, encryption-at-rest notes.
    - For SOC2: demonstrate access policies and change controls.

Output a **table or checklist** that links each security feature to its compliance coverage.

---

### 🧪 Security Testing & Verification

Include a **Security Testing Checklist** with these dimensions:
- ✅ Authentication logic tested (valid/invalid/missing token)
- ✅ Brute-force and rate limiting simulated
- ✅ SQLi/XSS/CSRF attempts blocked or logged
- ✅ Session hijack and token reuse checked
- ✅ MFA bypass tested
- ✅ Headers scanned using tools like Mozilla Observatory or OWASP ZAP
- ✅ Compliance coverage checklist generated
- ✅ Penetration test coverage (manual or tool-based) documented

---

### 📦 Output Expectations

Your deliverables should include:

- 📁 `src/` folder with all implementation files (modular and readable)
- 🧾 `README.md` with:
  - Setup instructions
  - Security rationale and diagrams
  - Links to relevant libraries/tools
- 🔐 `security-checklist.md` – security + compliance test checklist
- 📄 `compliance-map.md` – table linking features to GDPR/HIPAA/SOC2 controls
- 📝 Sample log output (JSON or syslog format)

---

### 💡 Optional Enhancements
- Provide a **security architecture diagram** (e.g., using Mermaid or textual sketch)
- Suggest and justify **OAuth provider or 3rd party service** (e.g., Auth0, AWS Cognito)
- Recommend secrets management strategy (e.g., Vault, AWS Secrets Manager)

---

### ⚠️ Constraints

- DO NOT use insecure libraries or demo defaults.
- DO NOT skip validations or hardcode credentials.
- DO NOT assume frontend implementation.

---
