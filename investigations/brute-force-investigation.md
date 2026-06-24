# Brute Force Investigation

## Objective

Investigate multiple failed login attempts against a Windows workstation.

---

## Alert Details

- Event ID: 4625
- Severity: Medium
- Source: Windows Security Log

---

## Investigation Process

1. Reviewed authentication logs.
2. Identified repeated failed logins.
3. Checked for successful authentication after failures.
4. Correlated timestamps.
5. Verified source IP address.

---

## MITRE ATT&CK

| Technique | Description |
|------------|-------------|
| T1110 | Brute Force |

---

## Findings

Repeated failed logins from the same IP indicated a possible brute-force attack.

---

## Recommended Actions

- Enable account lockout policy.
- Block malicious IP.
- Continue monitoring authentication events.
