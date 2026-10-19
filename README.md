# OpenCode breach — evidence images

Screenshots supporting the reports in [anomalyco/opencode#56833](https://github.com/anomalyco/opencode/issues/56833).

## `opencode-console-api-keys-oct2026.png`

OpenCode Console → Service Accounts → API Keys, showing all keys with:

- **Status: `Expired`**
- **Expires: `Never`** (for the two named keys)
- **Last used: Oct 17**

A key with no expiry date cannot expire on its own. All keys stopped on the same
day, which points to a bulk revocation rather than per-key expiry.

Personal identifiers (account email, mail header) are redacted.
