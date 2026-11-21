# Verified vendor offboarding playbook

**Trigger:** termination, unacceptable risk, insolvency or strategic replacement.

| Step | Owner | Required proof |
|---|---|---|
| Activate alternative delivery service and reconcile in-flight orders | Operations | Transition plan, order reconciliation, sign-off |
| Stop new data feeds; revoke API keys, tokens, SSO accounts and driver integrations | IT Security | Revocation logs, negative access test |
| Export necessary business records securely | Data/Operations | Transfer manifest, receipt and reconciliation |
| Delete vendor and sub-processor personal data, subject to legal retention exceptions | Vendor / Privacy | Signed deletion certificate, data categories, dates, sub-processor confirmations |
| Disable webhooks and network allowlists, rotate secrets | IT Security | Change tickets and configuration evidence |
| Close disputes, incidents, contractual and privacy obligations | Legal / Privacy | Closure checklist |
| Archive evidence and close vendor register entry | GRC | Signed exit review and evidence index |

**Acceptance criteria:** independently verify integration revocation; verify data transfer and deletion documentation; document lawful retention exceptions with controls and deletion dates; obtain operational and Privacy sign-off. Vendor self-attestation alone may require corroboration based on risk.

**Case status:** planned exit procedure, not an executed offboarding. No deletion certificate or access log exists in this simulated case.
