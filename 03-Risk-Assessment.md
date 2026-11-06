# 03. Information Security Risk Assessment

## Objective

For this stage, I've identified 10 potential security risks facing Harrow & Lane LLP.

The firm handles confidential legal documents and client information, so the assessment focuses on protecting that data and keeping important systems available.

## Risk Scoring Method

I'm using a simple 5×5 risk matrix.

**Likelihood**

1 = Rare  
2 = Unlikely  
3 = Possible  
4 = Likely  
5 = Almost certain

**Impact**

1 = Insignificant  
2 = Minor  
3 = Moderate  
4 = Major  
5 = Severe

**Risk Score = Likelihood × Impact**

| Score | Rating | Approach |
|---|---|---|
| 1–5 | Low | Monitor |
| 6–10 | Medium | Review and consider treatment |
| 11–15 | High | Prioritise treatment |
| 16–25 | Critical | Escalate and treat urgently |

This is my simplified risk methodology for the case study, not an ISO-prescribed scoring scale.

## Risk Register

| ID | Identified Risk | Likelihood | Impact | Initial Score | Risk Owner |
|---|---|---:|---:|---:|---|
| R01 | Phishing compromises a solicitor's email account | 4 | 5 | 20 (Critical) | IT Manager |
| R02 | Cloud document supplier suffers a data breach | 3 | 5 | 15 (High) | Compliance Officer |
| R03 | Ransomware affects employee laptops | 4 | 4 | 16 (Critical) | IT Manager |
| R04 | Incorrect file permissions expose client documents | 4 | 5 | 20 (Critical) | IT Manager |
| R05 | A laptop containing sensitive information is lost | 3 | 4 | 12 (High) | IT Manager |
| R06 | Former employees retain access to systems | 3 | 4 | 12 (High) | HR Manager |
| R07 | Backups fail during a recovery incident | 3 | 5 | 15 (High) | IT Manager |
| R08 | E-discovery supplier exposes client information | 3 | 5 | 15 (High) | Compliance Officer |
| R09 | Unpatched software is exploited | 4 | 4 | 16 (Critical) | IT Manager |
| R10 | Client records are retained longer than necessary | 3 | 4 | 12 (High) | Compliance Officer |

## Risk Treatment Plan

These are proposed actions. The fictional firm has not actually implemented them.

| Risk | Recommended Treatment | Target Score |
|---|---|---|
| R01 | Enforce MFA and provide phishing awareness training | 10 |
| R02 | Review supplier security evidence and contractual protections | 10 |
| R03 | Deploy endpoint protection and test recovery procedures | 8 |
| R04 | Review access permissions and restrict sensitive files | 10 |
| R05 | Encrypt laptops and enable remote device management | 8 |
| R06 | Introduce a formal leaver access-removal checklist | 4 |
| R07 | Schedule backup restoration tests and investigate failures | 10 |
| R08 | Assess e-discovery supplier security and access controls | 10 |
| R09 | Introduce regular patch monitoring and remediation | 8 |
| R10 | Establish retention periods and a secure deletion process | 8 |

Target scores are estimates of the risk remaining **if the proposed actions work**. They are not verified residual risk ratings.

## My Assessment

I would prioritise R01 and R04 because compromised email accounts and incorrectly shared documents could expose confidential client information.

For R01, I gave phishing a likelihood of 4 because staff regularly use email and may receive convincing malicious messages. I gave it an impact of 5 because a compromised account could expose sensitive legal communications.

That produces an initial score of 20, which is critical under my methodology.

MFA and staff training could reduce the likelihood of compromise, although the impact of a successful breach would remain serious.

## Limitations and Next Steps

The firm's current security controls have not been verified because this is a fictional scenario. In a real assessment, I would request evidence of existing controls before confirming the risk scores.

I would also record treatment progress, check whether controls are effective and review high-priority risks with the relevant owners.

For this exercise, critical risks should be reviewed by 20 November 2026, with the remaining risks reviewed by 6 December 2026.

This assessment is for learning and portfolio development, not a real security audit.
