# Incident Scenario

## Organization

Goldstar Financial Services is a fictional financial services company based in Chicago, Illinois. The company has approximately 450 employees and uses Microsoft 365 with Microsoft Entra ID for identity and access management.

## Affected User

Emily Carter is an Accounts Payable Specialist in the Finance department.

- Account: emily.carter@goldstar.example
- Work style: Hybrid
- Primary device: Company-managed Windows 11 laptop
- Primary browser: Microsoft Edge
- MFA method: Microsoft Authenticator
- Privilege level: Standard user

Emily normally accesses:

- Microsoft Outlook
- Microsoft Teams
- OneDrive
- SharePoint
- LedgerLink, a fictional finance SaaS application

## Initial Incident

Emily contacted the security team after receiving an unexpected Microsoft Authenticator prompt.

During the initial review, the security team also identified a recent OAuth consent event associated with an unfamiliar application named **DocuCloud PDF Tools**.

At this stage, it is not known whether the activity represents a successful account compromise, legitimate user activity, or another benign explanation.

## Initial Investigation Goal

Determine whether Emily Carter's Microsoft 365 identity was accessed or used by an unauthorized party and identify the scope and impact of any suspicious activity.

## Investigation Questions

1. Was Emily Carter's account accessed by an unauthorized party?
2. Did DocuCloud PDF Tools receive permissions that could allow access to Emily's Microsoft 365 data?
3. Was persistence established through OAuth permissions, tokens, or another identity mechanism?
4. What Microsoft 365 resources were accessed during the relevant time period?
5. Were any other identities, applications, or resources affected?
6. What containment and recovery actions are required?

## Initial Investigation Window

The initial investigation will review activity beginning 48 hours before the suspicious OAuth consent event and continuing through 48 hours after the incident was reported.

## Current Assessment

No conclusion has been reached regarding whether the account was compromised.

The investigation will rely on correlation between authentication activity, audit events, OAuth activity, MFA events, resource access, and other available evidence.
