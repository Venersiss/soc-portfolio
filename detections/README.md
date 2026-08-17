# detections/

Detection rules and the **reasoning** behind them. A rule without a rationale is just a regex.

## Template for each detection

```markdown
# Detection: <name>

## What it detects
One sentence.

## Why it matters
What adversary behavior does this catch? Reference MITRE ATT&CK technique IDs when possible.

## The rule
- Sigma / YARA / Splunk search syntax

## Log sources needed
- e.g. Windows Security (Event ID 4624), Sysmon, firewall logs

## Test
How I validated it: what attack I ran, what the rule fired on.

## False positives / tuning
What could trigger it legitimately and how I'd tune it.
```

## Planned

- [ ] First detection: logon anomaly (e.g. successful auth outside business hours)
- [ ] Second detection: suspicious process chain
- [ ] IOC-based rule from my own lab traffic
