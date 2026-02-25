# SOC Lab — Splunk SIEM & Linux Threat Detection

## Overview
A personal Security Operations Centre (SOC) lab focused on deploying,
operating, and documenting SIEM-based threat detection and incident
response workflows using Splunk and Linux endpoints.

## What This Repo Demonstrates
- Deployment and configuration of Splunk SIEM
- Linux endpoint log collection via Splunk Universal Forwarder
- Custom SPL detections mapped to MITRE ATT&CK techniques
- Alert triage and investigation workflows
- Structured incident response documentation

## Lab Architecture
- **SIEM:** Splunk Free (log ingestion, search, detection)
- **Monitored Endpoint:** Ubuntu Server 22.04
- **Log Forwarding:** Splunk Universal Forwarder
- **Host System:** Windows 11 (VirtualBox hypervisor)
- **Platform:** VirtualBox

## Detections Built
| Detection | MITRE Technique | Implementation |
|---|---|---|
| SSH Brute Force | T1110 | Planned |
| Unauthorized User Creation | T1136 | Planned |
| Suspicious File Modification | T1070 / T1565 | Planned |

## Incident Reports
| ID | Scenario | State |
|---|---|---|
| IR-001 | SSH Brute Force | Planned |
| IR-002 | Internal Reconnaissance | Planned |
| IR-003 | Privilege Escalation Attempt | Planned |

## Tools Used
Splunk Free · Splunk Universal Forwarder · Ubuntu Server 22.04  
VirtualBox · SPL · MITRE ATT&CK

## Status
Lab under active development. Content is added as each phase is completed.
