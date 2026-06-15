# Oil & Gas Incident Response Plan

## Purpose
Define how the organization identifies, escalates, contains, eradicates, recovers from, and learns from cybersecurity incidents affecting IT, OT, cloud, AI, and third-party services.

## Severity Levels
| Severity | Description | Example |
|---|---|---|
| SEV-1 | Safety, environmental, or major production impact | SCADA compromise affecting pipeline operations |
| SEV-2 | Significant business or operational impact | Ransomware on terminal scheduling systems |
| SEV-3 | Limited impact | Single compromised user account |
| SEV-4 | Low impact event | Blocked phishing attempt |

## Response Phases
1. Preparation
2. Detection and Analysis
3. Containment
4. Eradication
5. Recovery
6. Lessons Learned

## Oil & Gas Playbooks
- Ransomware affecting business systems
- SCADA or historian disruption
- Vendor remote access compromise
- Cloud data exposure
- AI system misuse or model integrity issue

## Key Roles
- Incident Commander
- IT Security Lead
- OT Security Lead
- Operations Representative
- Legal and Compliance
- Communications
- Vendor Manager
- Executive Sponsor

## Reporting Considerations
Security incidents involving pipeline operations may require rapid reporting to appropriate government and sector authorities depending on jurisdiction and asset type. Always validate reporting obligations with legal and compliance teams.

# Example Playbook: SCADA Disruption

1. Confirm whether the disruption is cyber, operational, communications, or equipment related.
2. Escalate to OT Security Lead and Operations Control Center.
3. Preserve logs from SCADA servers, engineering workstations, remote access tools, firewalls, and jump hosts.
4. Restrict remote access if compromise is suspected.
5. Coordinate with operations before isolating systems that could affect safety or production.
6. Validate manual operating procedures and backup communications.
7. Restore from known-good configurations only after engineering approval.
8. Document timeline, root cause, control gaps, and corrective actions.

