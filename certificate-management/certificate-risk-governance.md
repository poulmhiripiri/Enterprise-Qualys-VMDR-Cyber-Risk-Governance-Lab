# Certificate Risk Governance

## Objective

Certificate management ensures that certificates are discovered, tracked, renewed and governed to reduce outage, trust and security risk.

## Why Certificate Governance Matters

Expired, weak or unmanaged certificates can cause service outages, failed integrations, user trust issues and security exceptions.

## Governance Controls

| Control | Description |
|---|---|
| Certificate Discovery | Identify certificates across systems and services |
| Ownership Assignment | Assign service owners for each certificate |
| Expiry Monitoring | Track expiry windows and renewal requirements |
| Renewal Workflow | Ensure renewal requests are planned before expiry |
| Exception Handling | Document accepted risk where certificates cannot be renewed immediately |
| Executive Reporting | Report high-risk certificates and upcoming expiries |

## Recommended Expiry Thresholds

| Time to Expiry | Action |
|---|---|
| 90 days | Notify owner and confirm renewal plan |
| 60 days | Escalate to service owner |
| 30 days | Escalate to IT/security leadership |
| 7 days | Treat as urgent operational risk |
| Expired | Raise incident or high-risk exception |
