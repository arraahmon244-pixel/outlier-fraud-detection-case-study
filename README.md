# outlier-fraud-detection-case-study
Cybersecurity case study on risk-based access control and fraud detection
# Risk-Based Access Control and Fraud Detection in Remote Work Platforms

## Overview
This project is a beginner-level cybersecurity case study that analyzes how remote AI work platforms
(such as Outlier) use layered security and risk-based access control to prevent fraud, abuse, and
compliance violations.

The focus is on defensive security mechanisms rather than bypass techniques.

---

## Problem Statement
Remote work platforms face threats including:
- Identity fraud
- Location spoofing (e.g., VPN usage)
- Account sharing
- Device manipulation
- Payment fraud

Simple allow-or-block security controls are insufficient to handle these threats.

---

## Threat Model
The main threats considered in this case study include:
- Inconsistent IP geolocation and network signals
- Unstable device fingerprints
- Behavioral anomalies caused by shared or compromised accounts
- Fraudulent payment methods

---

## Defensive Security Controls
The platform applies defense-in-depth using multiple layers:

- **Network Layer**
  - IP reputation analysis
  - ASN (Autonomous System Number) checks

- **Device Layer**
  - Device fingerprinting
  - Browser and OS consistency checks

- **User Behavior Layer**
  - Behavioral biometrics (typing patterns, interaction timing)

- **Risk Engine**
  - Signal correlation
  - Cumulative risk scoring

- **Payment Layer**
  - KYC (Know Your Customer)
  - AML (Anti-Money Laundering) verification

---

## Risk-Based Access Control
Instead of immediate blocking, the system assigns a dynamic risk score to each account.
As risk increases, enforcement actions may include:
- Task limitations
- Delayed payouts
- Manual review
- Account suspension

This approach reduces false positives while maintaining strong security.



## Key Cybersecurity Insight
> Effective security systems focus on detecting inconsistencies across multiple signals
> rather than relying on a single indicator.

---

## Skills Demonstrated
- Threat modeling
- Fraud detection fundamentals
- Access control concepts
- Ethical cybersecurity analysis
- Real-world platform security understanding

---

## Author
**Ar Rahmon Idris**  
Cybersecurity Student (Beginner)
