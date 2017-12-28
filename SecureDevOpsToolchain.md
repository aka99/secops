#  Building a DevSecOps Program (CALMS)

**Culture**

Break down barriers between Development, Security, and Operations through education and outreach

**Automation**

Embed self-service automated security scanning and testing in continuous delivery

**Lean**

Value stream analysis on security and compliance processes to optimize flow

**Measurement**

Use metrics to shape design and drive decisions

**Sharing**
Share threats, risks, and vulnerabilities by adding them to engineering backlogs


## Start Your DevOps Metrics Program
- Number of high-severity vulnerabilities and how long they are open 
- Build and deployment cycle time
- Automated test frequency and coverage
- Scanning frequency and coverage
- Number of attacks (and attackers) hitting your application

## First Steps in Automation
- Build a security smoke test (e.g., ZAP Baseline Scan)
- Conduct negative unit testing to get off of the happy path 
- Attack your system before somebody else does (e.g., Gauntlt) 
- Add hardening steps into configuration recipes (e.g., dev-sec.io)
- Harden and test your CI/CD pipelines and do not rely on developer-friendly defaults

# Secure DevOps Toolchain

## Pre-Commit

**Security activities before code is checked in to version control**

Threat Modeling/Attack Mapping:
- Attacker personas
- Evil user stories
- Raindance
- Mozilla Rapid Risk Assessment 
- OWASP ThreatDragon

Security and Privacy Stories:
- OWASP ASVS
- SAFECode Security Stories

IDE Security Plugins:
- DevSkim 
- FindSecurityBugs 
- PumaScan 
- SonarLint

Pre-Commit Security Hooks:
- git-hound
- git-secrets 
- Repo-supervisor 
- ThoughtWorks Talisman

Secure Coding Standards:
- CERT Secure Coding Standards 
- OWASP Proactive Controls

Manual and Peer Reviews:
- Gerrit
- GitHub pull request 
- GitLab merge request 
- Review Board

## Commit (Continuous Integration)

**Fast, automated security checks during the build and Continuous Integration steps**

Static Code Analysis (SCA):
- FindSecurityBugs 
- Brakeman
- ESLint
- Phan

Security Unit Tests:
- JUnit
- Mocha
- xUnit

Infrastructure as Code Analysis:
- ansible-lint 
- Foodcritic 
- puppet-lint 
- cfn_nag

Dependency Management:
- OWASP Dependency Check 
- Bundler-Audit
- Gemnasium
- PHP Security Checker 
-Retire.JS
- Node Security Platform

Container Security:
- Actuary Anchore
- Clair
- Dagda 
- Docker 
- Bench 
- Falco

Container Hardening:
- Bane
- CIS Benchmarks 
- grsecurity


## Acceptance (Continuous Delivery)
**Automated security acceptance, functional testing, and deep out-of-band scanning during Continuous Delivery**

Infrastructure as Code:
- Ansible 
- Chef 
- Puppet 
- SaltStack 
- Terraform 
- Vagrant

Immutable Infrastructure:
- Docker 
- rkt


Security Scanning:
- Arachni 
- nmap 
- sqlmap 
- sslyze 
- ZAP 
- ssh_scan

Cloud Configuration Management:
- AWS CloudFormation
- Azure Resource Manager
- Google Cloud Deployment Manager

Security Acceptance Testing:
- BDD-Security 
- Gauntlt 
- Mittn

Infrastructure Tests:
- Serverspec 
- Test Kitchen

Infrastructure Compliance Checks:
- HubbleStack 
- InSpec


## Production (Continuous Deployment)
**Security checks before, during, and after code is deployed to production**

Security Smoke Tests:
- ZAP 
- Baseline 
- Scan 
- nmap 
- ssllabs-scan

Configuration Safety Checks:
- AWS Config
- AWS Trusted Advisor 
- Microsoft Azure Advisor 
- Security Monkey 
- OSQuery
 
Secrets Management:
- Ansible Vault 
- Blackbox
- Chef Vault 
- Docker Secrets 
- Hashicorp Vault 
- Pinterest Knox

Cloud Secrets Management:
- AWS KMS
- Azure Key Vault 
- Google Cloud KMS
 
Cloud Security Testing:
- CloudSploit 
- Nimbostratus
 
Server Hardening:
- dev-sec.io 
- SIMP

Host Intrusion Detection:
- fail2ban 
- OSSEC 
- Samhain


## Operations
**Continuous security monitoring, testing, audit, and compliance checks**

Fault Injection:
- Chaos Kong 
- Chaos Monkey

Cyber Simulations:
- Game day exercises 
- Tabletop scenarios

Penetration Testing:
- Attack-driven defense 
- Bug Bounties
- Red team exercises

Threat Intelligence:
- Diamond Model 
- Kill Chain
- STIX
- TAXII

Continuous Scanning:
- OpenSCAP 
- OpenVAS 
- Prowler 
- Scout2 
- vuls

Blameless Postmortems:
- Etsy Morgue

Continuous Monitoring:
- grafana 
- graphite 
- statsd 
- seyren 
- sof-elk 
- ElastAlert 
- 411

Cloud Monitoring:
- CloudWatch 
- CloudTrail 
- Reddalert

Cloud Compliance:
- Cloud Custodian 
- Compliance Monkey 
- Forseti Security


