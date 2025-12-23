# Using-Common-Attack-Vectors

This repository documents a hands-on cybersecurity lab focused on identifying, executing, and analyzing common attack vectors used in real-world environments. The lab emphasizes offensive techniques alongside defensive controls and mitigation strategies based on industry standards such as OWASP and CISA guidance. This project was completed in a controlled lab environment for educational purposes only. 
## Objectives
- Perform and analyze common web, malware, network, and social engineering attacks
- Understand how attackers exploit vulnerabilities in systems and users
- Identify effective defensive measures and security controls
- Apply theoretical security concepts in a practical, hands-on environment

---

## Attack Vectors Covered

### 1. Injection & XSS Attacks
- Performed **DOM-based XSS** and **Reflected XSS** attacks
- Analyzed how unvalidated user input can be executed in the browser
- Successfully demonstrated unauthorized admin access through injection techniques
- Identified hidden functionality and sensitive endpoints

**Key concepts:**
- Input validation
- Output encoding
- OWASP Top 10 – Injection (A03)

---

### 2. Malware Attack
- Generated a malicious payload using **msfvenom**
- Executed the payload on a target system
- Established a session and collected system information using post-exploitation commands
- Demonstrated how malware enables unauthorized system access

**Key concepts:**
- Payload generation
- Remote access
- Endpoint compromise

---

### 3. Distributed Denial-of-Service (DDoS) Attack
- Simulated a DDoS scenario by recruiting multiple hosts
- Observed service degradation and connection failures
- Identified firewall and system resource exhaustion errors (PF state limits)
- Analyzed the impact of traffic flooding on availability

**Key concepts:**
- Botnets
- Traffic flooding
- Availability attacks

---

### 4. Social Engineering / Phishing
- Created a phishing email using the **Social Engineering Toolkit (SET)**
- Crafted a realistic phishing message to collect user credentials
- Demonstrated how human factors are often the weakest security control
- Linked phishing as a common initial access vector for ransomware attacks

**Key concepts:**
- Phishing
- Credential harvesting
- User awareness vulnerabilities

---

## Defensive Measures & Mitigation

For each attack vector, defensive strategies were researched and applied, including:

- **Injection/XSS**
  - Parameterized queries
  - Context-aware output encoding
- **Malware**
  - Endpoint protection
  - Sandboxing and regular patching
- **DDoS**
  - Traffic filtering and load balancing
  - Anomaly detection and rate limiting
- **Social Engineering**
  - Security awareness training
  - Multi-Factor Authentication (MFA)

Sources referenced include:
- OWASP Top 10
- CISA Phishing Guidance
- Industry security research articles

---

## Additional Research
Expanded analysis on **Phishing Attacks** as an initial access vector, tying concepts to real-world SOC monitoring and detection scenarios, including prior work with my **Splunk Home Lab** analyzing phishing email data.

---

## Skills & Tools Demonstrated
- Web application security testing
- XSS and injection exploitation
- Metasploit Framework
- msfvenom payload creation
- Social Engineering Toolkit (SET)
- Attack analysis and defensive planning
- Security documentation and reporting

---


