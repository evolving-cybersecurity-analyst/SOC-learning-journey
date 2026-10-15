# MITRE ATT&CK in Operation

## What is an Operation?

An Operation is a real incident when the adversary use a specific sequency of tactice and techniques.
Map an Operation means taking all the events that happened and placing them into the MITRE ATT&CK framework for understand exactly what moves the adversary made, in what sequence, and what they could do next.

## Why this matters in a SOC

When a SOC Analyst receives an alert, mapping it to the MITRE ATT&CK framework in the context of an operation allows them to: 
- Understand if it's an isolated attack or a coordinated campaign
- Predict the adversary's next move
- Stop the attack before the adversary proceeds to the next move

## Example: WannaCry, a ransomware that was first seen during May 2017, which affected more than 150 countries.

WannaCry is a worm that, once inside the network, self-propagates through remote service explotation. SMB (MS17-010)

**In enterprise enviroment WannaCry follow these tactics:**
- Execution: Windows Management Instrumentation 
- Persistence: Windows Service
- Privilege Escalation: Windows Service
- Stealth: Hidden Files and Directories
- Defense Impairment: Windows Permissions
- Discovery: File and Directory Discovery, Peripheral Device Discovery, Remote System Discovery, System Network Configuration Discovery 
- Lateral Movement: Exploitation of Remote Services, Lateral Tool Transfer, RDP Hijacking
- Command and Control: Asymmetric Cryptography, Multi-hop Proxy
- Impact: Data Encrypted for Impact, Inhibit System Recovery, Service Stop

## Reference: MITRE ATT&CK Navigator, WannaCry (Enterprise)
