# Luekrit Kongkamon

**Cloud Security Engineer  |  IAM & Identity Specialist  |  Melbourne, Australia**

I build AWS security automation and identity governance controls backed by real test evidence. Delivered a zero-incident Entra ID migration for a critical infrastructure organisation, more than 40 applications, 500+ users, and cut the phishing-prone rate from 13% to 4.8% in under three months. Currently sitting AWS SAA-C03 (Jun 2026) and SC-300 (Jul 2026).

---

## Featured Project

[![Cloud Security Automation](https://github.com/Luekrit/images-/blob/main/Cloud%20Security%20Automation%20and%20Remediation.png)](https://github.com/Luekrit/Cloud-Security-Automation)

### [Cloud Security Automation & Remediation](https://github.com/Luekrit/Cloud-Security-Automation)

Event-driven IAM security pipeline that detects unauthorised privilege escalation, runs governance-aware remediation logic, and sends structured alerts — end-to-end validated with real CloudWatch logs and SNS output.

**Stack:** CloudTrail · EventBridge · Lambda · SNS · DynamoDB · Terraform · Python/Boto3

- Detects `AttachUserPolicy` abuse in near real-time via CloudTrail and EventBridge
- DynamoDB exception registry with TTL — approved exceptions auto-expire, no manual cleanup
- Human-in-the-loop dry-run mode before live enforcement eliminates accidental lockout risk
- Lambda IAM role scoped to `iam-test-user` only — no over-permissioned execution role
- Handles the IAM/us-east-1 global service logging problem with a dedicated Terraform provider alias
- CloudTrail log file validation, SNS encryption, S3 SSE-KMS — hardened end to end
- Modular Terraform, S3 remote state, DynamoDB locking, AssumeRole — no long-term credentials

---

## Cloud Projects

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Luekrit/Automated-Cloud-Security-Monitoring-Remediation-AWS-/tree/main">
        <img src="https://github.com/Luekrit/images-/blob/main/Automated%20Cloud%20Security%20Monitoring%20%26%20Remediation%20(AWS).png" width="320"/>
        <br><b>Automated Cloud Security Monitoring & Remediation</b>
      </a>
      <br>S3 security controls, Python, Boto3, AWS automation
    </td>
    <td align="center">
      <a href="https://github.com/Luekrit/Enterprise-IAM-Governance-Lab-with-AI-Powered-Identity-Analytics-Automation">
        <img src="https://github.com/Luekrit/images-/blob/main/AI-Powered%20Identity%20Analytics.png" width="320"/>
        <br><b>Enterprise IAM Governance Lab</b>
      </a>
      <br>Joiner-Mover-Leaver automation in Python/Boto3. CloudTrail log parser with CloudWatch alerting for high-value IAM role changes.
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/Luekrit/Terraform-Secured-S3-EC2-IAM">
        <img src="https://github.com/Luekrit/images-/blob/main/Terraform%20%2B%20AWS%20S3%20%2B%20EC2%20%2B%20IAM.png" width="320"/>
        <br><b>Terraform Secured S3, EC2 & IAM</b>
      </a>
      <br>Infrastructure-as-Code with lifecycle management, least-privilege IAM roles, and encryption automation.
    </td>
    <td align="center">
      <a href="https://github.com/Luekrit/web-project-nextwork-">
        <img src="https://github.com/Luekrit/images-/blob/main/Java%20Web%20App%20Deployment%20with%20AWS%20CICD.png" width="320"/>
        <br><b>Java Web App Deployment with AWS CI/CD</b>
      </a>
      <br>EC2, S3, CodePipeline, CodeDeploy, CodeArtifact
    </td>
  </tr>
</table>

---

## Security Projects

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/Luekrit/Azure-Security-Operations-Threat-Detection">
        <img src="https://github.com/Luekrit/images-/blob/main/Azure%20Security%20Operations%20%26%20Threat%20Detection.png" width="350" height="210"/>
        <br><b>Azure Security Operations & Threat Detection</b>
      </a>
      <br>Deployed honeypot Azure VMs to capture real attacker traffic. Built KQL detection rules correlating Event ID 4625 with GeoIP data, generating Sentinel incidents with attacker context pre-attached.
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/Luekrit/Threat-Hunting-at-Australian-University-s-Incidents">
        <img src="https://github.com/Luekrit/images-/blob/main/Threat%20Hunting%20at%20an%20Australian%20University_1.png" width="350" height="210"/>
        <br><b>Threat Hunting — Australian University Incidents</b>
      </a>
      <br>Analysed three real incidents — ANU ransomware, WSU 580TB SSO exfiltration, QUT PrintNightmare. Full MITRE ATT&CK mapping with Navigator layer JSON.
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/Luekrit/SolarWinds-Cyber-Risk-Management-Program-SolarWinds-Case-Study-">
        <img src="https://github.com/Luekrit/images-/blob/main/SolarWinds%20Cyber%20Risk%20Management%20Program.png" width="350" height="210"/>
        <br><b>SolarWinds Cyber Risk Management</b>
      </a>
      <br>Applied ISO 27001 and NIST frameworks to the SolarWinds supply chain attack — risk evaluation, control prioritisation, executive reporting.
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/Luekrit/SOC-Analyst-Technical-Assessment">
        <img src="https://github.com/Luekrit/images-/blob/main/SOC%20assessment%20template_1.png" width="350" height="210"/>
        <br><b>SOC Analyst Technical Assessment</b>
      </a>
      <br>End-to-end SOC investigation framework covering SIEM analysis, log correlation, MITRE ATT&CK mapping, IR workflow, evidence handling, and executive reporting.
    </td>
  </tr>
</table>

---

## Stack

```
Cloud       AWS (CloudTrail, EventBridge, Lambda, SNS, DynamoDB, IAM, S3, Security Hub)
            Azure (Sentinel, Defender for Cloud, Entra ID)
IaC         Terraform (modular), CloudFormation
Languages   Python, Boto3, KQL, PowerShell, Bash, YAML
Identity    Entra ID, Okta, SAML, OIDC, OAuth, MFA, Conditional Access, RBAC
Security    MITRE ATT&CK, Cisco XDR, Rapid7 InsightVM, KnowBe4
Frameworks  NIST CSF 2.0, ISO 27001, ASD Essential Eight, APRA CPS 234
```

---

## Certifications

| Credential | Status |
|---|---|
| CompTIA Security+ | Achieved 2024 |
| CompTIA Network+ | Achieved 2024 |
| AWS Solutions Architect – Associate | Exam scheduled Jun 2026 |
| Microsoft SC-300: Identity & Access Administrator | Exam scheduled Jul 2026 |
| AWS Security Specialty | Planned Q4 2026 |

---

## Connect

[LinkedIn](https://www.linkedin.com/in/luekrit-kongkamon/) · luekrit.k@gmail.com
