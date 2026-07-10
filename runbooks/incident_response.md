# Incident Response Runbook

1. Detect — baseline JSON, endpoint query, or alert notification.
2. Contain — enable firewall block list for affected host; preserve logs/reports.
3. Analyze — compare current attestation baseline to known-good.
4. Remediate — apply change control, rerun baseline, restore control set.
5. Post-incident — review evidence chain; include signed artifacts and hashes.

## Evidence requirement

Include baseline JSON and signed output package in post-incident review.
