# Risk Assessment - Weak Passwords

## 1. Asset

User Accounts (Internal Systems, Applications, VPN Access)

## 2. Asset Owner

IT / Security Team

## 3. Description

User accounts provide access to organizational systems and data. Weak passwords increase the likelihood of unauthorized access and compromise of sensitive information.

---

## 4. Threats

* Brute force attacks
* Credential stuffing
* Password guessing
* Phishing attacks

## 5. Vulnerabilities

* Short or simple passwords
* Reused passwords across systems
* Lack of Multi-Factor Authentication (MFA)
* No account lockout mechanism
* Weak password policy enforcement

---

## 6. Risk Scenario

An attacker obtains user credentials through credential stuffing or guessing due to weak passwords. This results in unauthorized access to internal systems and potential data breach.

---

## 7. Impact Analysis

| Impact Area      | Description                               | Severity |
| ---------------- | ----------------------------------------- | -------- |
| Confidentiality  | Exposure of sensitive data                | High     |
| Integrity        | Unauthorized data modification            | Medium   |
| Availability     | Potential account lockout / system misuse | Medium   |
| Legal/Compliance | GDPR violation, fines                     | High     |
| Reputation       | Loss of customer trust                    | High     |

**Overall Impact: High**

---

## 8. Likelihood Analysis

| Factor            | Evaluation                       |
| ----------------- | -------------------------------- |
| Ease of attack    | High (automated tools available) |
| Exposure          | High (internet-facing systems)   |
| Existing controls | Low / insufficient               |

**Likelihood: High**

---

## 9. Risk Level

**Risk = High Likelihood x High Impact -> CRITICAL**

---

## 10. Existing Controls

* Basic password requirements (length >= 8)
* No enforced MFA
* No password reuse prevention

---

## 11. Recommended Controls (Risk Treatment)

### Preventive Controls

* Enforce strong password policy (min. 12 characters)
* Implement Multi-Factor Authentication (MFA)
* Enforce password uniqueness
* Introduce password blacklist (common passwords)

### Detective Controls

* Monitor failed login attempts
* Implement alerting for suspicious login activity
* Log authentication events

### Corrective Controls

* Account lockout after failed attempts
* Forced password reset after compromise
* Incident response procedure

---

## 12. Risk Treatment Plan

| Action                        | Owner       | Priority | Deadline |
| ----------------------------- | ----------- | -------- | -------- |
| Implement MFA                 | IT Security | High     | 30 days  |
| Update password policy        | GRC Team    | High     | 14 days  |
| Configure account lockout     | IT Team     | Medium   | 30 days  |
| Implement monitoring & alerts | SOC Team    | Medium   | 45 days  |

---

## 13. Residual Risk

After implementing controls:

* Likelihood: Medium
* Impact: High

**Residual Risk Level: Medium**

---

## 14. Risk Owner

Head of IT / CISO

## 15. Review Date

Next review: 12 months or after major security incident
