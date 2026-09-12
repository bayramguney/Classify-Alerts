# Classify-Alerts
# Lab - Classify Alerts

## Overview

This lab focused on researching Snort IDS alerts and CVE vulnerabilities, then classifying alerts in both Windows and Linux enterprise environments. The objective was to determine whether alerts represented true positives, false positives, or required additional investigation based on the operating systems and devices present in each environment.

## Objectives

- Research Snort SID and CVE identifiers.
- Identify associated vulnerabilities and CVSS severity scores.
- Understand malware signatures and vulnerability-based alerts.
- Classify alerts as True Positive, False Positive, or Needs Further Investigation.
- Compare alert relevance across Windows and Linux environments.

## Skills Demonstrated

- Snort IDS alert analysis
- CVE research using MITRE, NVD, and Cisco Talos
- CVSS severity interpretation
- Security event classification
- Threat analysis
- Windows security assessment
- Linux security assessment
- SIEM alert validation
- Vulnerability assessment

## Technologies Used

- Snort IDS
- MITRE CVE Database
- National Vulnerability Database (NVD)
- Cisco Talos
- VirusTotal
- CVSS v3.x

## Key Findings

- Windows-specific vulnerabilities generated true positives only in Windows environments.
- Linux kernel and APT vulnerabilities were relevant only in Linux environments.
- Malware alerts required evaluating whether the targeted operating system existed in the environment.
- Some alerts affecting Apple devices required additional investigation because unmanaged devices could still appear on enterprise networks.
- Accurate alert classification helps reduce false positives while improving incident response efficiency.

## Outcome

This lab strengthened practical SOC analyst skills by combining vulnerability research with security event analysis. It reinforced how analysts validate IDS alerts, interpret CVE information, and determine whether security events require investigation based on the organization's infrastructure.
