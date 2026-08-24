# NIST CSF 2.0 Cybersecurity Risk Assessment

## Project Overview

This project demonstrates a basic cybersecurity risk assessment using the NIST Cybersecurity Framework 2.0. The assessment was performed against Gulf Coast Financial Services, a fictional financial services organization with approximately 250 employees.

The purpose of the project was to identify cybersecurity control gaps, evaluate the risks associated with those gaps, and recommend security controls that could reduce organizational risk.

## Environment

The fictional organization uses the following technologies:

* Microsoft 365
* Microsoft Entra ID
* Microsoft Defender
* Windows 11 endpoints
* SharePoint and OneDrive
* Cloud based business applications
* Third party SaaS applications
* VPN remote access

The organization handles sensitive information including customer financial information, employee personally identifiable information, authentication credentials, and internal business records.

## Assessment Methodology

The NIST Cybersecurity Framework 2.0 was used to evaluate cybersecurity risks within the organization.

The assessment focused on identifying the current state of selected security controls, determining potential cybersecurity risks, assigning risk levels, and recommending remediation actions.

The findings were mapped to applicable NIST CSF functions, including Protect, Respond, and Recover.

## Key Findings

Five cybersecurity risks were identified during the assessment.

### 1. Multi Factor Authentication

MFA was enabled for administrator accounts but was not required for all standard user accounts.

**Risk:** Compromised credentials could allow unauthorized access to organizational systems and sensitive information.

**Recommendation:** Require MFA for all organizational user accounts through Microsoft Entra ID.

### 2. Password Security

Strong password requirements were not consistently enforced across organizational accounts.

**Risk:** Weak passwords increase the likelihood of account compromise and unauthorized access.

**Recommendation:** Implement and enforce stronger password requirements for all organizational accounts.

### 3. Patch Management

Security updates were not consistently applied to all Windows workstations.

**Risk:** Attackers could exploit known vulnerabilities on unpatched systems.

**Recommendation:** Establish a patch management process to regularly deploy and verify security updates across organizational endpoints.

### 4. Incident Response

The organization did not maintain a documented cybersecurity incident response plan.

**Risk:** An uncoordinated response could increase the operational impact of a cybersecurity incident and delay containment.

**Recommendation:** Develop and maintain an incident response plan defining responsibilities, communication procedures, and response actions.

### 5. Backup and Recovery

Critical business information was regularly backed up, but restoration testing was not routinely performed.

**Risk:** Backup failures could prevent the organization from recovering critical information following a cybersecurity incident.

**Recommendation:** Conduct scheduled restoration testing to verify that critical information can be successfully recovered.

## Risk Summary

The assessment identified five high risk findings requiring remediation. Priority areas included identity and access management, password security, patch management, incident response planning, and backup recovery testing.

## Skills Demonstrated

* Governance, Risk, and Compliance
* NIST Cybersecurity Framework 2.0
* Cybersecurity Risk Assessment
* Risk Identification
* Risk Analysis
* Risk Prioritization
* Security Control Evaluation
* Identity and Access Management
* Vulnerability Management
* Incident Response
* Remediation Planning
* Security Documentation

## Project Documentation

The repository contains the complete NIST CSF 2.0 assessment spreadsheet, organization profile, risk summary, and supporting screenshots.

### Organization Profile

![Organization Profile](Screenshots/01-company-profile.png)

### NIST CSF 2.0 Assessment

![NIST CSF Assessment](Screenshots/02-nist-csf-assessment.png)

### Risk Summary

![Risk Summary](Screenshots/03-risk-summary.png)

## Disclaimer

Gulf Coast Financial Services is a fictional organization created solely for educational and portfolio purposes. No real company data or confidential information was used in this assessment.
