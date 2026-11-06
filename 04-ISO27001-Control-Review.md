# 04. ISO 27001 Control Review

## Purpose

In the previous stage, I identified 10 information security risks affecting Harrow & Lane LLP.

For this stage, I've selected 12 controls from ISO 27001:2022 Annex A that could help manage those risks.

The aim is to understand which controls are relevant, why they matter and what evidence I would need to check.

## Priority Control Mapping

| ISO Control | Related Risk | Why I've Selected It |
|---|---|---|
| A.5.15 Access control | R04 | Limit access to confidential client documents. |
| A.5.18 Access rights | R04, R06 | Review permissions and remove access when employees leave. |
| A.5.19 Supplier security | R02, R08 | Manage security risks involving external service providers. |
| A.5.23 Cloud security | R02, R08 | Address risks from cloud document storage and other cloud services. |
| A.5.34 Personal information protection | R02, R10 | Protect personal data handled by the firm. |
| A.6.3 Security awareness training | R01 | Help employees recognise phishing attempts. |
| A.8.5 Secure authentication | R01 | Strengthen account security through MFA and appropriate authentication. |
| A.8.7 Malware protection | R03 | Reduce the risk of ransomware affecting company devices. |
| A.8.8 Technical vulnerability management | R09 | Identify vulnerable software and prioritise patches. |
| A.8.10 Information deletion | R10 | Remove information safely when retention periods expire. |
| A.8.13 Information backup | R07 | Support recovery when important systems or data become unavailable. |
| A.8.24 Use of cryptography | R05 | Protect sensitive data stored on laptops and other devices. |

## Applicability and Implementation Status

All 12 controls above are provisionally marked as applicable because they address risks identified in this case study.

However, I haven't verified whether the fictional firm has implemented them.

**Status: Proposed / Not verified**

I would need to collect evidence before marking any control as implemented.

## Example: Phishing Risk

Risk R01 concerns a solicitor's email account being compromised through phishing.

I selected two controls:

- **A.6.3:** Security awareness training to help staff identify suspicious emails.
- **A.8.5:** Secure authentication to reduce the likelihood of unauthorised account access.

For evidence, I would request staff training records, the firm's MFA configuration and relevant account security policies.

I would then check whether the controls are operating as intended before reassessing the risk.

## Example: Supplier Data Breach

Risk R02 involves a breach at the firm's cloud document provider.

I selected A.5.19 and A.5.23 because the firm depends on external organisations to store sensitive client information.

I would request the supplier's security documentation, contractual security commitments and incident notification arrangements.

The firm would still need to manage supplier risk even though it does not directly control the supplier's infrastructure.

## Limitations

This is an initial control review rather than a completed Statement of Applicability.

ISO 27001:2022 Annex A contains 93 controls. I have selected 12 for detailed consideration and would need to assess the remaining 81 before preparing a complete Statement of Applicability.

For each control, I would record whether it is applicable, the reason for inclusion or exclusion, the implementation status and the evidence supporting that decision.

This is a fictional learning exercise. No real security controls have been tested or implemented.
