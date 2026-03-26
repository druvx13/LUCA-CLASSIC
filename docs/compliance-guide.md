# LUCA – CLASSIC Compliance Guide

## Quick Operational Principle

You can use the work broadly (including commercially), but if you distribute, you must preserve notice/license continuity and avoid adding downstream restrictions.

## A) Distributor Checklist (Release Gate)

- [ ] Include full license text in the release package/repository.
- [ ] Keep original copyright notice.
- [ ] Add conspicuous notice that LUCA – CLASSIC applies.
- [ ] If modified: indicate modifications clearly.
- [ ] If derivative is distributed: include license copy or canonical link.
- [ ] Confirm no additional rights restrictions are imposed on recipients for licensed components.
- [ ] Remove/avoid trademark endorsement language without permission.
- [ ] Preserve disclaimers when redistributing.

## B) Internal Use vs Distribution

### Internal-only use

The text’s strict operational conditions are primarily distribution-oriented. Internal evaluation/use without distribution usually has lower compliance overhead.

### External distribution

Triggers strongest obligations: notice preservation, pass-through license continuity, and no additional restrictions.

## C) Contribution Intake Process

When accepting contributions:

1. Ask contributors to confirm originality/right-to-submit.
2. Record contribution channel (PR, patch, email).
3. Ensure contributors understand their submission is licensed under LUCA – CLASSIC terms.
4. Preserve traceability for audit and dispute defense.

## D) Product Packaging Patterns

### Source distribution

- Root `LICENSE` file included.
- Header notices in major source files.
- Changelog marking modifications.

### Binary distribution

- Include license in installer/about/legal notices.
- Provide URL/path to full license in packaged docs.
- Ensure downstream terms do not contradict Section 4(b).

### SaaS/web deployment

Even without binary distribution, provide legal notices where feasible to reduce ambiguity and improve compliance posture.

## E) Risk and Legal Management

- Patent teams should review Sections 3 and 10.2.
- Procurement/legal should evaluate India law/venue/arbitration posture.
- Customer contracts should avoid promising licensor warranties that license disclaims.
- Track indemnity risk in Section 7 for enterprise deployments.

## F) Non-Compliance Recovery Playbook

1. Identify violated clause.
2. Stop affected distribution channel if needed.
3. Repackage artifacts with corrected notices/license terms.
4. Remove conflicting restrictions and endorsement claims.
5. Redeploy corrected package and maintain incident record.

