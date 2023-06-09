# Cyber Threat Intelligence

1. [Threat Intelligence](#threat-intelligence)
2. [Data Loss Prevention and Mobile Endpoint Protection](#data-loss-prevention-and-mobile-endpoint-protection)
3. [Scanning](#scanning)
4. [Application Security and Testing](#application-security-and-testing)
5. [SIEM Platforms](#siem-platforms)
6. [Threat Hunting](#threat-hunting)

## Threat Intelligence

* Threat intelligence - info about threats & threat actors that helps mitigate incidents.

* Threat intelligence strategy:

  * Collect - integrate data
  
  * Process - put data in context

  * Analyze - find insight & actions

  * Share - inform decisions

* Intelligence areas - Tactical, Operational, Strategic

* Threat intelligence platform capabilities:

  * Collect
  * Correlate
  * Enrichment & Contextualization
  * Analyze
  * Integrate
  * Act

* Best practices - Intelligence detection:

  * Predict & prioritize security weaknesses
  * Detect deviations to identify malicious activity
  * React in real time to exploits

* Security intelligence - real-time collection, normalization & analytics of data generated by users, apps & infra that impacts IT security & risk posture of an organization.

## Data Loss Prevention and Mobile Endpoint Protection

* Top challenges for data security:

  * Explosive data growth
  * New privacy regulations
  * Operational complexity
  * Cybersecurity skills shortage

* Common pitfalls in data security:

  * Failure to move beyond compliance
  * Failure to recognize need for centralized data security
  * Failure to define who owns responsibility for data
  * Failure to adddress known vulnerabilities
  * Failure to prioritize & leverage data activity monitoring

* Data protection capabilities:

  * Data discovery
  * Data classification
  * Vulnerability assessment
  * Data risk analysis
  * Data & file activity monitoring
  * Real-time alerting
  * Blocking, masking & quarantining
  * Active analytics
  * Encryption
  * Tokenization
  * Key management
  * Automated compliance report

* Mobile endpoints differ from traditional endpoints in the following manner:

  * Users don't interact directly with OS
  * Apps act as broker between user and OS
  * OS stability can be easily monitored
  * AV software can check apps and read certain signatures, but cannot peek inside the app contents

* Daily operations in mobile endpoint protection:

  * Monitor device OS versions
  * Monitor app installs and versions
  * Monitor & enforce encryption
  * Distribute secure payloads
  * Automate compliance actions
  * Ensure proper NAC policies are enforced
  * Educate users regularly
  * Update contingency plans

## Scanning

* Vulnerability scanner capabilities:

  * Keeping updated database of vulnerabilities
  * Detection of genuine vulnerabilities without a lot of false positives
  * Performing trend analysis and generating reports
  * Provide recommendations for countermeasures

* Vulnerability scanner components:

  * Engine scanner
  * Database
  * Report module
  * UI

* CVSS (Common Vulnerability Scoring System) - system of assigning severity rankings to vulnerabilities; provides a standardized score across the industry.

* Values of CVSS - base score (exploitability & impact subscore), temporal score and environmental score.

* Types of port scans:

  * Ping
  * TCP Connect
  * Stealth
  * TCP (half open)
  * UDP

## Application Security and Testing

* In architecture, Enterprise and Solution (more detailed) architecture break down the problem, providing different levels of abstraction.

* High-level architectures are described through Architectural Building Blocks (ABBs) and Solution Building Blocks (SBBs).

* The use of security architecture patterns accelerate the creation of a solution architecture.

* Application security threats:

  * Input validation - buffer overflow, XSS, SQLi.

  * Authentication - network eavesdropping, bruteforce attack, dictionary attack.

  * Authorization - privesc, data tampering, luring attacks.

  * Configuration management - unauthorized access, retrieval of cleartext config data.

  * Exception management - info disclosure, denial of service.

  * Auditing & logging - exploitation without trace, denying an operation.

## SIEM Platforms

* SIEM (System Information Event Management) - data aggregator, search & reporting system; collects logs for analysis.

* SIEM system can be rule-based or employ a statistical correlation engine to establish relationships between event log entries.

* Normalization - parsing raw event data and preparing it for readability; allows for consistent storage and indexing (for fast searching & sorting).

## Threat Hunting

* Cyber threat hunting - proactively identifying, intercepting, tracking, investigating & eliminating cyber adversaries as early as possible in the Cyber Kill Chain.
