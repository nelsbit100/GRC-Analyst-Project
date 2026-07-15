# Nonconformity Report (NCR) - Template

## NCR ID: NCR-2026-001
## Date: 2026-07-10
## Auditor: [Auditor Name]

### 1. Description of Nonconformity
Requirement A.9.2 requires MFA for all administrative access. During the audit, it was discovered that 3 out of 10 admin accounts on the "CloudSecure Admin Portal" did not have MFA enabled.

### 2. Root Cause Analysis
Default user creation scripts in the Internal Portal did not enforce MFA via the IAM provider.

### 3. Corrective Action Plan
* **Immediate:** Force reset passwords and enable MFA for the 3 accounts.
* **Long-term:** Update provisioning scripts to mandate MFA during user creation.

### 4. Status
[ ] Open [ ] Remediation In Progress [X] Closed