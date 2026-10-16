# Phishing Email Investigation Methodology

## 1. Purpose

This document explains the process used to investigate a suspected phishing email in a simulated Security Operations Center (SOC) environment.

## 2. Investigation Workflow

### Step 1: Initial Triage
Review the sender, recipient, subject line and email body.

Look for suspicious urgency, unexpected requests, unusual sender details and attempts to obtain sensitive information.

### Step 2: Evidence Collection
Preserve the supplied email sample and document the information available.

Record missing evidence, including original email headers, URLs, attachments and relevant security logs.

### Step 3: Indicator Analysis
Identify any actual domains, URLs, IP addresses or file hashes present in the evidence.

Use approved security tools to examine relevant indicators when available. Record the source and result of each check.

Do not invent indicators or interpret an absence of data as proof that an email is safe.

### Step 4: Risk Assessment
Evaluate the evidence and determine whether the case is suspicious, benign, confirmed malicious or inconclusive.

Explain the reasoning behind the classification and identify any uncertainty.

### Step 5: Response Recommendations
Recommend actions proportionate to the evidence, such as reporting the message, verifying the request through an official channel, reviewing relevant logs and escalating confirmed threats.

### Step 6: Documentation
Record the investigation steps, evidence, findings, limitations and recommended next actions in the incident report.

## 3. Evidence Handling

- Use fictional or authorized training data.
- Do not expose passwords, personal information or confidential company data.
- Avoid opening suspicious links or attachments on a personal computer.
- Record the tools used and the results observed.
- Distinguish verified findings from assumptions.

## 4. Tools

- GitHub: Project documentation and version control.
- VirusTotal: Reputation checks for available public indicators.
- URLScan.io: Review of available URL scan results.
- CyberChef: Decoding and transforming data for analysis.

Tool results must be interpreted in context. A clean reputation result does not guarantee that an indicator is safe.

## 5. Limitations

This project uses a fictional email sample. No actual email headers, malicious URLs, attachments or organizational logs were provided.

The exercise demonstrates an initial triage methodology, not a confirmed real-world security incident.

## 6. Conclusion

A structured investigation helps an analyst collect evidence, assess risk, communicate uncertainty and recommend appropriate security actions.
