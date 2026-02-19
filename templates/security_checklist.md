# Agent Security & Compliance Checklist

## 1. Input Validation
- [ ] Prompt injection detection implemented.
- [ ] Sanitization of user-provided data.
- [ ] Rate limiting on input streams.

## 2. Output Safety
- [ ] Content filtering for harmful or biased output.
- [ ] PII (Personally Identifiable Information) detection and redaction.
- [ ] Formatting validation (e.g., JSON schema checks).

## 3. Tool & API Security
- [ ] Least privilege access for all tool integrations.
- [ ] Secure storage of API keys and secrets.
- [ ] Audit logging for all external tool calls.

## 4. Data Protection
- [ ] Encryption of data at rest and in transit.
- [ ] Data retention policies defined and enforced.
- [ ] Access control models (RBAC/ABAC) implemented.

## 5. Monitoring & Response
- [ ] Anomaly detection for agent behavior.
- [ ] Incident response plan for security breaches.
- [ ] Regular security audits and vulnerability scans.

## 6. Compliance
- [ ] Adherence to GDPR/CCPA or relevant privacy laws.
- [ ] Ethical AI guidelines followed.
- [ ] Documentation of compliance measures.
