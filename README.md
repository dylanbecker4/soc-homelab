# Cybersecurity Homelab

I built this homelab to practice my cybersecurity skills and get more comfortable working through security problems on my own. I’m interested in SOC/Blue Team work, network security, and identity management, so I’m using this repository to document what I build, test, and learn along the way.

My goal is to understand what’s happening behind the tools—what caused an event, what evidence it left behind, and how I would investigate it.

## Projects

### Security Monitoring and Investigations

I use my Windows and Wazuh environment to generate activity, review alerts, and practice investigating security events. My write-ups explain what I tested, what appeared in the logs, and what I learned.

[View investigation write-ups](investigations/)

### Cloud Identity and Detection

- [Toronto Raptors Entra ID Lab](azure/entra-id-raptors/README.md) — I set up test users and groups, delegated password resets to a help desk account, and investigated audit and sign-in logs.
- [Raptors Security Operations — Microsoft Sentinel Lab](azure/raptors-sentinel/README.md) — I connected Entra audit logs to Sentinel, wrote a KQL rule to detect admin password resets, and investigated and closed a test incident as Benign Positive.

## Skills I’m Practicing

- Investigating security alerts and reading logs
- Managing Windows Server and Active Directory
- Managing cloud identities and permissions
- Applying least privilege
- Troubleshooting authentication and access issues
- Documenting findings with screenshots and explanations

## How I Approach Each Lab

1. Choose a skill or scenario to practice.
2. Configure the environment and run a controlled test.
3. Review the logs and check whether the result matches what I expected.
4. Document the findings, troubleshooting, and lessons learned.

## What’s Next

- Build a Python log-analysis tool
- Create a phishing email analysis project
- Expand cloud identity testing and monitoring
- Continue practicing investigations across my lab environments

This repository is a work in progress as I keep learning. All testing is performed in environments I own or am authorized to use. Screenshots are reviewed and sensitive details are removed before publication.
