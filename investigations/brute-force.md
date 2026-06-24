# Brute Force Investigation

## Scenario

Multiple failed login attempts were detected against a Windows workstation.

---

## Objective

Determine whether the activity indicates a brute-force attack.

---

## Detection

Windows Security Event ID:

4625

Multiple failed login attempts from the same source.

---

## Investigation Steps

1. Review failed authentication logs.
2. Identify source IP.
3. Check for successful logins.
4. Correlate timestamps.
5. Determine if account lockout occurred.

---

## MITRE ATT&CK

Technique: T1110 – Brute Force

---

## Conclusion

The activity was classified as suspicious authentication behavior.

Recommended actions:

- Block the offending IP address.
- Enable account lockout policies.
- Continue monitoring for repeated attempts.
