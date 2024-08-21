# NIST 800-37 Rev. 2 RMF (Risk Management Framework)
* Risk avoidance -> reduce (mitigate) -> transfer -> accept
* What level of risk is acceptable for a system? 
* When to use? Protect sensitive information, develop/implement new system, after security breach, making changes to system
1) Prepare - upfront planning
* Align RMF process with organizational objectives/risk management strategy 
2) Categorize the System
* Think: What type of data? Credit cards -> PCI DSS, PHI -> HIPAA, etc.
* How does the information system impact the system? CIA Triad (low, moderate, high) 
* NIST 800-60 - help determine appropriate security categorization of information and information systems
3) Select security controls
* Pick out controls from NIST 800-53 control families
4) Implement Security Controls
* Can take a long time, control implementations should not cripple required functionality
5) Assess Security Controls
* Security Assessor/Auditor
* Is the security controls implemented correctly, operating as intended, and producing desired outcome?
6) Authorize the System
* AO (Authorizing Official) signs off/formally documents and accept remaining risk within the system
7) Monitor the Controls/System
* New vulnerabilities/threats on the system? remediate/respond to them
* Changes to system signed off by AO ideally do not increase risk

# NIST 800-53 Security and Privacy Controls
* Catalog of security and privacy controls used to create robust security frameworks to help protect against cybersecurity threats
* Control families 
- Access control (AC)
- Audit and accountability (AU)
- Configuration management (CM)
- Incident Response (IR)
- Maintenance (MA)
- Media Protection (MP)
- Personnel Security (PS)
- Risk Assessment (RA)
- etc. 

* Also low-medium-high security requirements and control enhancements
* Implementing more controls than necessary may unnecessarily reduce functionality of a system (balance: usability, functionality, and security)
* Compliance, risk management, and standardization

# NIST 800-61 Computer Security Incident Handling Guide
* Outlines how to respond to computer security incidents
* Incident Response Lifecycle
1) Preparation - create incident response plan
2) Detection & Analysis - detect and confirm occurance of security incident
3) Containment Eradication & Recovery 
4) Post-Incident Activity - post-mortem analysis to identify areas for improvement, updating incidence response plans, etc.
* Continuous improvement is key
* Being Prepared

# NIST CSF (Cybersecurity Framework)
* Identify, protect, detect, response, recover
* Identify - NIST 800-53/CIS Critical Security Controls (Center for Internet Security) e.g. data protection, account management, etc.
* (CIS controls have implementation groups: low, moderate, high)
* Risk assessment, policy developement, gap analysis, incident response planning, continuous improvement

# Other Frameworks
## HIPAA - PHI
* HITRUST - HIPAA compliance
* Security rule/privacy rule
* Breach Notification Rule

## PCI DSS
* Credit cards
* Determine scope of CDE - cardholder data environment 
* Full track data - cannot store (anatomy of CC)
* ISA - internal security assessors
* QSA - qualified security assessors

## GDPR - General Data Protection Regulation (EU)

