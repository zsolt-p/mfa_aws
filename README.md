# `aws-cli` with MFA

Generates `mfa` profile to existing AWS session. Requests a `session_token` to enable authentication on API calls that require MFA.

# Requirements

1. Existing `aws` session (run `aws configure` first)
2. Exisging MFA device linked to the account

# Usage

```bash
$ mfa_aws
Please enter your AWS MFA token: XXXXXX
==> aws-cli authenticated with MFA device.
==> Append '--profile mfa' to API calls requiring MFA.
==> Expiry: 2019-12-11T01:47:57Z
```
