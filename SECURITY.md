# OpenROAD Initiative Security Policy

## Introduction

The OpenROAD Initiative takes the security of our open source EDA ecosystem seriously. We encourage responsible reporting of any security vulnerabilities found in our projects.

## Scope of this policy

This policy applies specifically to security vulnerabilities and sensitive data exposures within OpenROAD Initiative project repositories. If the respository is a fork, please report it to the upstream project according to their security policy.

### In scope (Please report via this policy):
- Security vulnerabilities in software source code that could allow attackers to compromise a user's machine (e.g., executing malware or viruses)
- Vulnerabilities that could introduce malicious backdoors or unauthorized alterations into generated hardware designs
- Inadvertent disclosures of sensitive or restricted data, including but not limited to NDA-protected PDK data, accidental exposure of confidential files, or the submission of content not intended for public distribution

### Out of scope (Please report via standard GitHub Issues):
- Software bugs that lead to application crashes, incorrect behavior, or unintended execution
- Flow integrity issues, including the silent corruption of design data across flow stages
- Non-deterministic behavior affecting the reproducibility of results
- Incorrect transformations or logic errors during synthesis, placement, routing, or timing anlysis

## Reporting a Vulnerability

If you have discovered a vulnerability or data exposure that falls within the scope of this policy, please do not open a public GitHub issue. Instead, please send a disclosure notice via email to: security@openroadinitiative.org.

### What to Include
Please provide as much information as possible to help the project maintainers investigate the vulnerability, including:
- The repository and specific component where the vulnerability exists
- A detailed description of the vulnerability or data exposure
- Steps to reproduce the issue (if applicable)
- Any potential impact on users or generated designs

## Response and Disclosure Timeline

### Acknowledgment
We will acknowledge receipt of your vulnerability report within 3 working days.

### Coordinated Disclosure
We adhere to a 90-day coordinated disclosure timeline. We will work with you to understand the issue, develop a fix, and coordinate a public release. This timeline may be adjusted based on mutual agreement depending on the severity and impact of the vulnerability.
