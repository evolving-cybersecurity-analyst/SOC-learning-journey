# MITRE ATT&CK Framework

## What is it?

MITRE ATT&CK (Tactic, Technique and Procedure) 

According to MITRE's official documentation:
> "is a globally-accessible knowledge base of adversary tactics and techniques based on real world observation."

## Tactic (The "Why") 
An adversary's goal or objective. 
MITRE provides 15 tactics:
- Reconnaissance
- Resource Development
- Initial Access
- Execution 
- Persistence
- Privilege Escalation 
- Stealth 
- Defense Impairment
- Credential Access
- Discovery 
- Lateral Movement
- Collection 
- Command and Control 
- Exfiltration 
- Impact 

## Why it's a Matrix, not a sequence
Unlike the Cyber Kill Chain or Unified Kill Chain (that represent several steps in order), ATT&CK is a matrix: an attacker can use any tactic in any order, and often repeat tactics.

## Technique (The "How")
There are more than 200 Techniques and more than 450 Sub-Techniques across 15 Tactics in the Enterprise domain. 

These techniques are used every day in real world environment, so it is crucial to understand the adversary tactics and techniques, and the MITRE Framework helps us to deal with every day incident and to map and stop the adversary before it can have a negative impact on the enviroment.

A Technique is a specific method or tool an adversary uses to achieve a Tactic. 
For example, under the "Credential Access" tactic, an adversary might use the technique "Network Sniffing" or "Brute Force". 

## Example

Let's consider the "Initial Access" tactic:
- **Technique**: Phishing - Send malicious email to trick user into clicking link or opening attachments
- **Technique**: Exploit Public-Facing Application - Attack vulnerable web applications exposed to the internet

A SOC analyst monitoring the techniques might set alerts for: 
- Multiple failed login attempts (Brute Force indicator)
- Suspicious email attachments
- Web application exploit attempts

## Why this matters in a SOC

Understanding ATT&CK techniques allows a SOC team to: 
- Map alerts to attacker behavior
- Communicate incidents using a standardized language
- Prioritize threats based on known adversary tactics
- Build detection rules before incidents occur

## Reference: MITRE ATT&CK 
