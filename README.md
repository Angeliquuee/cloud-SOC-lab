
Welcome to my **Security Operations Center (SOC)** Lab repository! This project documents my hands-on experience building and configuring a cloud-based security lab using Microsoft Azure and Microsoft's security ecosystem. This SOC lab is based on learning resources and lab exercises from **The Cyber Range**. 

The goal of this lab is to develop practical skills in security monitoring, vulnerability management, endpoint detection and response (*EDR*), threat detection, and security information and event management (*SIEM*).

I will use this repository to document lab configurations, technical walkthroughs, detection rules, investigation workflows, lessons learned, and security findings. 

## Objectives

- Build and configure a cloud-based security lab using Microsoft Azure.
- Explore vulnerability management and identify security weaknesses.
- Configure endpoint detection and response capabilities.
- Collect, analyze, and correlate security logs.
- Create and investigate security alerts using SIEM tools.
- Develop threat detection and incident response workflows.
- Document hands-on projects and continuously improve my cybersecurity skills.

## Tools & Technologies

| Tool                  | Category                 | Purpose                                                                                      |
| --------------------- | ------------------------ | -------------------------------------------------------------------------------------------- |
| Microsoft Azure       | Cloud platform           | Host and manage cloud resources for the lab.                                                 |
| Tenable VM            | Vulnerability management | Identify, assess, prioritize, and track vulnerabilities.                                     |
| Defender for Endpoint | EDR                      | Monitor endpoints, investigate alerts, and detect suspicious activity.                       |
| Microsoft Sentinel    | SIEM / SOAR              | Collect and analyze security data, detect threats, and support incident response automation. |
## Comparable Technologies

| Category                 | Comparable Products                                                    |
| ------------------------ | ---------------------------------------------------------------------- |
| Cloud Platform           | AWS, Google Cloud Platform (GCP), IBM Cloud, Oracle Cloud              |
| Vulnerability Management | Rapid7 InsightVM, Qualys, OpenVAS, Greenbone                           |
| EDR                      | CrowdStrike Falcon, SentinelOne, VMware Carbon Black                   |
| SIEM / SOAR              | Splunk, IBM QRadar, Elastic Security, Crowdstrike Falcon Next-Gen SIEM |

## Lab Architecture

The lab will use Microsoft Azure as the cloud environment, with security tools supporting vulnerability assessment, endpoint monitoring, and centralized security analysis.

**Planned workflow:**

1. **Cloud Infrastructure:** Deploy and configure the necessary Azure resources.
2. **Vulnerability Management:** Scan lab assets with Tenable and review identified vulnerabilities.
3. **Endpoint Security:** Configure Microsoft Defender for Endpoint to monitor endpoint activity.
4. **Log Collection:** Collect relevant security events and integrate supported data sources.
5. **Threat Detection:** Use Microsoft Sentinel to analyze logs, create detection rules, and investigate incidents.
6. **Incident Response:** Document investigation steps, findings, and potential remediation actions.

> **Note:** This architecture describes the planned workflow. Components and integrations will be updated as the lab develops.



## Projects & Documentation

This section will track completed lab exercises and investigations.

| Project                  | Description                                                                       | Status  |
| ------------------------ | --------------------------------------------------------------------------------- | ------- |
| Azure Lab Setup          | Deploy and configure the lab environment.                                         | Planned |
| Vulnerability Assessment | Scan lab assets and analyze vulnerability findings using Tenable.                 | Planned |
| Endpoint Monitoring      | Configure endpoint visibility and investigate alerts using Defender for Endpoint. | Planned |
| Sentinel Integration     | Connect supported data sources and explore log analysis.                          | Planned |
| Detection Engineering    | Develop and test analytics rules and KQL queries.                                 | Planned |
| Incident Investigation   | Analyze security alerts and document incident response workflows.                 | Planned |


_Project statuses will be updated as each exercise is completed._

## Skills I'm Developing

- Cloud security fundamentals
- Vulnerability assessment and remediation
- Endpoint detection and response (EDR)
- Security information and event management (SIEM)
- Security orchestration, automation, and response (SOAR)
- Log analysis and correlation
- Kusto Query Language (KQL)
- Threat detection and investigation
- Incident response documentation
- Security configuration and hardening

## Documentation Format

Each lab exercise or investigation will aim to include:

1. **Objective**: What I am trying to accomplish.
2. **Environment**: Tools, resources, and configurations involved.
3. **Procedure**: Step-by-step implementation.
4. **Evidence**: Relevant screenshots, queries, logs, or findings.
5. **Analysis**: What the results indicate and why they matter.
6. **Remediation**: Recommended fixes or response actions, where applicable.
7. **Lessons Learned**: Key takeaways and opportunities for improvement.

## Security & Responsible Use

All activities in this repository are intended for authorized lab environments, defensive security research, and educational purposes.

- Only scan systems and assets I own or have explicit permission to assess.
- Avoid publishing credentials, API keys, tokens, subscription IDs, private IP information when sensitive, or other confidential data.
- Sanitize screenshots, exported logs, and incident artifacts before committing them.
- Use synthetic or appropriately sanitized data when sharing security investigations.
- Follow applicable licensing terms and the responsible-use guidelines for each tool.

## Learning Resources

- [Microsoft Azure Documentation](https://learn.microsoft.com/en-us/azure/)
- [Microsoft Defender for Endpoint Documentation](https://learn.microsoft.com/en-us/defender-endpoint/)
- [Microsoft Sentinel Documentation](https://learn.microsoft.com/en-us/azure/sentinel/)
- [Tenable Documentation](https://docs.tenable.com/)
- [Kusto Query Language (KQL) Documentation](https://learn.microsoft.com/en-us/kusto/query/)
- [The Cyber Range](https://www.skool.com/cyber-range/about?ref=bbc8b0bb80344a7cb52283fca619adb2)

## Progress & Future Goals

This repository is a living record of my SOC lab journey. As I gain experience, I plan to expand the lab with additional data sources, detection scenarios, vulnerability assessments, threat investigations, and incident response exercises.

My focus is on building practical, demonstrable skills that align with real-world Security Operations Center workflows.

---

**Disclaimer:** This repository is for educational and defensive cybersecurity purposes only. All testing will be conducted in authorized environments.