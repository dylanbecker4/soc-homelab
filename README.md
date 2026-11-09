# Cybersecurity Homelab

I built this homelab to practice my cybersecurity skills and get more comfortable working through security problems on my own. I’m interested in SOC and blue team work, network security, and identity management, so I use this repository to document what I build, test, and learn along the way.

My goal is to understand what’s happening behind the tools: what caused an event, what evidence it left behind, and how I’d investigate it.

## Projects

### Security Monitoring and Investigations

I use my Windows and Wazuh lab to generate activity, review alerts, and practice investigating security events. My write-ups cover what I tested, what showed up in the logs, and what I learned.

[View investigation write-ups](investigations/)

### Cloud Identity and Detection

- [Toronto Raptors Entra ID Lab](azure/entra-id-raptors/README.md) — I created test users and groups, delegated password resets to a help desk account, and investigated audit and sign-in logs.
- [Raptors Security Operations — Microsoft Sentinel Lab](azure/raptors-sentinel/README.md) — I connected Entra audit logs to Sentinel and built a scheduled analytics rule using KQL to detect admin password resets. I traced a test alert back to the original audit event and closed the incident as **Benign Positive**.

## Skills I’m Practicing

- Investigating security alerts and correlating events across logs
- Managing Windows Server and Active Directory
- Managing cloud identities and applying least privilege
- Writing KQL queries and building scheduled detections in Microsoft Sentinel
- Troubleshooting authentication and access issues
- Documenting findings with screenshots and explanations

## How I Approach Each Lab

1. Pick a skill or scenario I want to practice.
2. Set up the environment and run a controlled test.
3. Review the logs and compare the results with what I expected.
4. Document what happened, what I had to troubleshoot, and what I’d change next time.

## What’s Next

- Build a Python tool to summarize authentication logs and flag repeated failures.
- Create a phishing email analysis project focused on headers, links, and indicators.
- Test whether overlapping Sentinel query windows produce duplicate password reset alerts.

All testing takes place in environments I own or am authorized to use. I review screenshots and remove sensitive details before posting them.
