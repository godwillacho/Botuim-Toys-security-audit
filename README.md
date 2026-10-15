# Botium Toys: Security Controls and Compliance Audit

An internal IT security audit of Botium Toys, a fictional toy retailer with a storefront, offices and a warehouse, serving customers in the E.U. Completed as part of the Google Cybersecurity Professional Certificate.

The audit assesses which security controls are in place, checks compliance against three frameworks, and recommends remediations to the IT manager.

**Deliverable:** [`Botium_Toys_Security_Audit.docx`](Botium_Toys_Security_Audit.docx)

## Scope

- **Controls assessment:** administrative, technical and physical controls across the company's assets
- **Compliance review:** PCI DSS, GDPR, and SOC 1 / SOC 2

## Key Findings

| Area | Gap | Risk |
|---|---|---|
| Access control | All employees can access internal and customer data | No least privilege or separation of duties; insider and breach risk |
| Data protection | Cardholder data and PII are not encrypted | PCI DSS and GDPR non-compliance |
| Identity | Minimal password requirements, no password manager | Credential compromise |
| Detection | No intrusion detection system | Intrusions may go unnoticed |
| Resilience | No backups or disaster recovery plan | Loss of critical data and business continuity |
| Asset management | Assets inventoried but not classified | Controls cannot be prioritised by sensitivity |

**Controls already in place:** firewall with defined rules, monitored antivirus, legacy system maintenance, physical locks, CCTV, and fire detection and prevention.

## Recommendations

1. Enforce least privilege and separation of duties, starting with access to cardholder data and payroll.
2. Encrypt cardholder data and PII at rest and in transit.
3. Strengthen password policy and deploy a password management system.
4. Deploy an intrusion detection system.
5. Implement regular backups and a documented disaster recovery plan.
6. Classify inventoried assets to prioritise controls.
