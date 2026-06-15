# Oil & Gas Vendor Risk Assessment Guide

## Purpose
Assess third-party cybersecurity and operational risk for oil and gas vendors, including cloud providers, MSPs, OT integrators, equipment manufacturers, inspection firms, consultants, and AI providers.

## Vendor Risk Factors
- Access to OT or production systems
- Access to confidential data
- Remote access privileges
- Safety or environmental impact
- Cloud hosting or data processing
- AI model or data handling
- Subcontractor dependency
- Incident notification capability

## Risk Ratings
| Rating | Criteria |
|---|---|
| Low | No sensitive access, low business impact |
| Medium | Internal data or limited operational access |
| High | Sensitive data, privileged access, or business-critical dependency |
| Critical | OT access, safety impact, pipeline/refinery operational dependency |

## Minimum Requirements for High/Critical Vendors
- MFA for remote access
- Named security contact
- Incident notification terms
- Evidence of vulnerability management
- Access review and least privilege
- Data protection and deletion terms
- Business continuity and disaster recovery evidence
- Subcontractor controls

# Vendor Cybersecurity Questionnaire

| Question | Vendor Response | Evidence Requested |
|---|---|---|
| What services are provided? | | Contract/SOW |
| Will the vendor access OT, SCADA, historian, or production systems? | | Architecture diagram |
| Is MFA enforced for remote access? | | Policy or screenshot |
| How are privileged accounts managed? | | Access control policy |
| What data will be stored or processed? | | Data flow diagram |
| Is customer data used to train AI models? | | AI/data use policy |
| What is the incident notification timeframe? | | Contract clause |
| Are backups tested? | | Test evidence |
| Are subcontractors used? | | Subprocessor list |

