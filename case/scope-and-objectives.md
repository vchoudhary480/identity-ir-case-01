# Investigation Scope and Objectives

## Purpose

This investigation will determine whether the Microsoft 365 identity belonging to Emily Carter was accessed or used by an unauthorized party.

The investigation will focus on identity, authentication, OAuth, MFA, and Microsoft 365 activity related to the suspected incident.

## Primary Objectives

The investigation will attempt to determine:

1. Whether Emily Carter's account experienced unauthorized access.
2. Whether the DocuCloud PDF Tools application was legitimately authorized by Emily.
3. What permissions were granted to the application.
4. Whether those permissions could have allowed access to Microsoft 365 data.
5. Whether suspicious authentication or MFA activity occurred around the same time.
6. Whether any Microsoft 365 resources were accessed after the suspicious events.
7. Whether persistence was established through OAuth permissions, tokens, or another identity mechanism.
8. Whether any additional users, applications, or resources appear to have been affected.

## Investigation Scope

### In Scope

The investigation will review synthetic evidence related to:

- Microsoft Entra ID sign-in activity
- Entra ID audit activity
- OAuth consent and application permissions
- MFA-related events
- Microsoft 365 resource access
- Relevant IP addresses, devices, applications, and user agents
- Activity associated with Emily Carter
- Activity associated with DocuCloud PDF Tools
- Events within the defined investigation window

## Investigation Time Window

The initial review window begins 48 hours before the suspicious OAuth consent event and continues through 48 hours after the incident was reported.

The investigation window may be expanded if evidence shows relevant activity outside the initial period.

## Out of Scope

Unless evidence later requires additional investigation, the following are outside the initial scope:

- Endpoint malware analysis
- Network packet capture analysis
- Investigation of unrelated employees
- Physical security investigation
- Financial fraud investigation
- Attribution of the activity to a specific real-world threat actor

## Evidence Standard

No single unusual sign-in, IP address, location, MFA event, or application event will be treated as proof of compromise.

Conclusions will be based on correlation between multiple evidence sources.

Possible legitimate explanations will be considered before activity is classified as suspicious or malicious.

## Limitations


The investigation is designed to simulate a Microsoft Entra ID incident response process and does not represent an investigation of a real organization, user, or Microsoft tenant.
