# SOC Homelab: Active Directory and Wazuh

## Overview
I built this lab to practice Windows administration and develop
the investigation skills needed for a cybersecurity analyst role.

My goal is to collect security logs, investigate suspicious activity,
and document findings with evidence and recommended next steps.

## Lab Environment
- VMware Workstation
- Windows Server 2025 domain controller with Active Directory and DNS
- Windows 11 domain-joined client
- Ubuntu server running Wazuh

## Current Progress
- Configured Active Directory and DNS.
- Joined a Windows 11 client to the domain.
- Installed Wazuh and accessed its web dashboard.

## Planned Investigations
- Collect and investigate Sysmon events from the Windows client.
- Analyze failed logins followed by a successful login.
- Monitor changes to privileged Active Directory groups.
- Create and test a custom detection rule.

## Investigation Documentation
Each investigation will include:
- The scenario and lab setup
- Relevant logs and screenshots
- Investigation steps and findings
- Recommended response
- Limitations and possible false positives
