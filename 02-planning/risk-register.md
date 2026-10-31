# Risk Register — Project Genesis

| Metadata | Details |
|---|---|
| **Document ID** | GEN-RSK-001 |
| **Project Name** | Project Genesis — Enterprise Operational Infrastructure & Service Workflows Launch |
| **Document Type** | Risk Register |
| **Project Location** | Bousher and Barka, Sultanate of Oman |
| **Reference Framework** | PMI — PMBOK® Guide, Google Project Management Framework |
| **Assessment Method** | Qualitative Probability × Impact (P × I) |
| **Document Owner** | Lead Project Manager |
| **Version** | 1.0 |
| **Status** | Pending Approval |
| **Last Updated** | 25 October 2026 |
| **Review Frequency** | Weekly, with immediate reviews when material risk triggers occur |
| **Related Document** | `01-initiation/project-charter.md` (GEN-CH-001) |

---

## 1. Executive Summary

This Risk Register identifies, assesses, and monitors threats that could affect the successful delivery of Project Genesis, an initiative to establish the digital infrastructure, operational workflows, commercial documentation, and initial client outreach capabilities of an IT and business services enterprise in the Sultanate of Oman.

The register covers technical, cybersecurity, legal and regulatory, financial, contractual, operational, schedule, and market-related risks.

The project will use a tailored probability-impact assessment method appropriate to its scope, duration, budget, and resource model.

The initial register identifies eleven risks. Risk ratings are preliminary estimates and must be reviewed against actual project conditions, vendor quotations, stakeholder decisions, and regulatory advice.

The Risk Register is a controlled project document. The Lead Project Manager is responsible for maintaining it, coordinating mitigation actions, monitoring changes in exposure, and escalating material risks to the Project Sponsor.

**Priority attention is required for:**

- Personal data protection and applicable regulatory compliance.
- Cybersecurity, credential management, and organizational ownership of digital assets.
- Budget uncertainty and dependencies on external contractors.
- Timely approval of technical, legal, and business deliverables.

A risk is not considered closed merely because a mitigation action has been planned. Closure requires evidence that the risk has been resolved, is no longer relevant, or has been formally accepted by the authorized decision-maker.

---

## 2. Risk Assessment Methodology

### 2.1 Probability Scale

Probability represents the estimated likelihood that a risk event will occur during the project or the relevant initial operational period.

| Rating | Classification | Definition |
|---:|---|---|
| 1 | Rare | Very unlikely to occur |
| 2 | Unlikely | Possible, but not expected under normal conditions |
| 3 | Possible | Could reasonably occur |
| 4 | Likely | Expected to occur under current conditions |
| 5 | Almost Certain | Expected to occur unless conditions change |

### 2.2 Impact Scale

Impact represents the severity of the consequences for project objectives, cost, schedule, quality, security, business continuity, or legal and regulatory compliance.

| Rating | Classification | Definition |
|---:|---|---|
| 1 | Negligible | Minimal disruption with no material effect on project objectives |
| 2 | Minor | Limited rework or disruption manageable within normal task execution |
| 3 | Moderate | Noticeable delay, additional cost, or rework requiring Project Manager intervention |
| 4 | Major | Material threat to a milestone, budget baseline, service availability, or a critical deliverable |
| 5 | Critical | Potential serious legal or regulatory consequences, major security or data incident, critical data loss, or threat to project viability |

Impact must be assessed using the most significant reasonably foreseeable consequence. A legal or security risk may therefore receive an impact rating of 5 even when its estimated probability is low.

### 2.3 Risk Score Calculation

The initial risk score is calculated as:

`Risk Score = Probability × Impact`

| Score | Rating | Required Management Response |
|---:|---|---|
| 1–6 | Low | Monitor and implement proportionate controls |
| 8–12 | Medium | Assign mitigation actions and review regularly |
| 15–25 | High | Prioritize mitigation, assign clear deadlines, and report to the Project Sponsor |

The thresholds above are consistent with the possible products of integer probability and impact ratings from 1 to 5.

The score is a prioritization tool and does not replace professional judgment. Material legal, regulatory, privacy, or security concerns must be escalated when necessary, regardless of their numerical score.

### 2.4 Risk Response Strategies

The following response strategies are used:

- **Avoid:** Change the approach to eliminate the risk exposure.
- **Mitigate:** Reduce the likelihood of occurrence, the impact, or both.
- **Transfer / Share:** Allocate an appropriate portion of the exposure to a qualified third party through suitable contractual or operational arrangements.
- **Accept:** Acknowledge the risk and monitor it where the exposure is within approved tolerance.
- **Escalate:** Refer the risk to the Project Sponsor or another authorized decision-maker when it exceeds the Lead Project Manager's authority or risk tolerance.

Risk acceptance must be documented when the exposure is material or exceeds normal operational tolerance.

---

## 3. Risk Log

Initial scores represent the risk exposure before the planned mitigation actions have been verified as effective.

| Risk ID | Category | Risk Description | P | I | Initial Score | Priority | Response Strategy | Risk Owner | Status |
|---|---|---|---:|---:|---:|---|---|---|---|
| RSK-001 | Technical / Cloud | Delays, misconfiguration, or unnecessary complexity in the selected cloud and collaboration architecture. | 2 | 4 | 8 | Medium | Mitigate | Lead Software & Cloud Engineer | Open |
| RSK-002 | Legal / Regulatory | Delays or compliance gaps concerning commercial registration, applicable business licenses, tax obligations, or other relevant Omani requirements. | 2 | 5 | 10 | Medium | Mitigate | Lead Project Manager | Open |
| RSK-003 | Operational / Scope | Uncontrolled scope expansion during planning, execution, or stakeholder review. | 3 | 4 | 12 | Medium | Mitigate | Lead Project Manager | Open |
| RSK-004 | Financial | Budget overrun caused by unconfirmed contractor fees, legal expenses, recurring subscriptions, or infrastructure costs. | 3 | 4 | 12 | Medium | Mitigate | Project Sponsor | Open |
| RSK-005 | Commercial / Contractual | Client disputes or unclear expectations concerning service scope, contractual terms, deliverables, or SLA commitments. | 2 | 4 | 8 | Medium | Mitigate | Lead Project Manager | Open |
| RSK-006 | Technical / Connectivity | Connectivity or service performance problems affecting the intended operating locations or public website. | 2 | 3 | 6 | Low | Mitigate | Lead Software & Cloud Engineer | Open |
| RSK-007 | Privacy / Regulatory | Failure to identify or comply with applicable personal data protection requirements when collecting, processing, storing, or using personal data. | 3 | 5 | 15 | High | Mitigate / Escalate | Lead Project Manager | Open |
| RSK-008 | Cybersecurity | Unauthorized access, credential exposure, data loss, or compromise of company systems and digital assets. | 3 | 5 | 15 | High | Mitigate | Lead Software & Cloud Engineer | Open |
| RSK-009 | Contractor / Asset Ownership | Loss of critical knowledge, disputed ownership, or failure to transfer code, documentation, credentials, or other project assets from contractors. | 3 | 4 | 12 | Medium | Mitigate | Lead Project Manager | Open |
| RSK-010 | Schedule / Dependencies | Delays in legal review, content approval, vendor onboarding, or stakeholder decisions threaten the eight-week schedule. | 3 | 4 | 12 | Medium | Mitigate | Lead Project Manager | Open |
| RSK-011 | Market / Client Outreach | Low initial response from target SME clients reduces the effectiveness of the initial outreach campaign. | 3 | 3 | 9 | Medium | Mitigate | Marketing Lead | Open |

**Risk ownership principle:** Each risk has one accountable owner. Supporting contributors may assist with mitigation, but accountability for tracking the risk and reporting its status remains with the designated owner.

---

## 4. Risk Mitigation and Action Plans

### RSK-001 — Cloud Architecture and Configuration

**Initial Exposure:** 2 × 4 = 8 (Medium)

**Risk Statement:** The selected cloud, collaboration, hosting, or identity configuration may introduce implementation delays, misconfiguration, unnecessary complexity, or avoidable operating costs.

**Mitigation Actions:**

- Confirm and document the target architecture before production deployment.
- Use Google Workspace for corporate collaboration and document management where appropriate.
- Use AWS or another approved provider for website hosting only where justified by the technical requirements and budget.
- Configure least-privilege access and multi-factor authentication (MFA) for supported accounts.
- Validate DNS, HTTPS, hosting, access permissions, and required service integrations.
- Document backup, recovery, administrative access, and service ownership.
- Apply infrastructure-as-code tooling only where it provides a clear benefit for the selected architecture.

**Risk Trigger / Early Warning:** Unresolved architecture decisions, repeated configuration failures, unexpected vendor charges, or delays in environment readiness.

**Risk Owner:** Lead Software & Cloud Engineer.

**Supporting Roles:** Lead Project Manager.

**Target:** Architecture agreed before production configuration; verification completed before website launch.

**Residual Risk:** To be reassessed after implementation and testing.

### RSK-002 — Commercial Registration and Regulatory Requirements

**Initial Exposure:** 2 × 5 = 10 (Medium)

**Risk Statement:** Incorrect or outdated assumptions about the company's Commercial Registration (CR), authorized activities, licensing requirements, tax obligations, or other applicable legal requirements may cause delays, compliance gaps, or restrictions on planned services.

**Mitigation Actions:**

- Verify the latest official CR information and the exact registered activity descriptions.
- Confirm whether any planned activity requires additional registration, authorization, or licensing.
- Engage the External Legal Adviser early to review relevant business requirements.
- Identify tax and administrative obligations that apply to the planned operations.
- Maintain a compliance action list with an accountable owner and target date.
- Store registration and other sensitive business records in an access-controlled location.
- Do not publish sensitive registration details in a public GitHub repository.

**Risk Trigger / Early Warning:** Unverified activity codes, contradictory registration information, missing approvals, or legal advice identifying an authorization gap.

**Risk Owner:** Lead Project Manager.

**Supporting Roles:** External Legal Adviser and Project Sponsor.

**Target:** Verification completed before publication of definitive service claims or commencement of any activity requiring authorization.

**Residual Risk:** To be reassessed after the required verification and legal review.

### RSK-003 — Scope Creep

**Initial Exposure:** 3 × 4 = 12 (Medium)

**Risk Statement:** Additional requirements may be introduced without formal evaluation, resulting in schedule delays, budget pressure, reduced quality, or incomplete delivery of the approved objectives.

**Mitigation Actions:**

- Use the approved Project Charter (GEN-CH-001) as the scope baseline.
- Require documented Change Requests for additions affecting scope, schedule, budget, security, quality, or legal compliance.
- Assess the delivery impact before recommending approval.
- Obtain Project Sponsor approval for material changes.
- Record approved and rejected changes in the project change log.
- Keep excluded activities, including construction and unapproved payment gateway implementation, outside the project baseline unless formally authorized.

**Risk Trigger / Early Warning:** New deliverables appearing in the backlog without approval, unbudgeted requests, or repeated changes to agreed acceptance criteria.

**Risk Owner:** Lead Project Manager.

**Supporting Roles:** Project Sponsor and relevant delivery contributors.

**Target:** Continuous throughout the project.

**Residual Risk:** To be reassessed during weekly reviews.

### RSK-004 — Budget Overrun

**Initial Exposure:** 3 × 4 = 12 (Medium)

**Risk Statement:** The provisional budget of USD 1,500–2,500 may be insufficient if contractor fees, legal review, recurring subscriptions, infrastructure usage, or administrative expenses are not fully accounted for.

**Mitigation Actions:**

- Confirm the budget baseline and cost inclusions before committing expenditure.
- Obtain vendor and contractor quotations where practicable.
- Separate one-time costs, recurring subscriptions, contractor fees, legal expenses, and contingency.
- Configure budget alerts and applicable spending controls with cloud providers.
- Track actual expenditure, commitments, and forecast costs weekly.
- Require approval before committing expenditure beyond delegated limits or the approved budget.
- Identify lower-cost alternatives if forecasts exceed the budget envelope.

**Risk Trigger / Early Warning:** Forecast cost exceeds the authorized budget, material costs remain unquoted, or recurring subscription costs are omitted from the estimate.

**Risk Owner:** Project Sponsor.

**Supporting Roles:** Lead Project Manager and relevant contributors.

**Target:** Cost baseline confirmed before significant commitments; weekly monitoring throughout delivery.

**Residual Risk:** To be reassessed after the cost baseline is approved and quotations are confirmed.

### RSK-005 — Contractual and Service Governance Disputes

**Initial Exposure:** 2 × 4 = 8 (Medium)

**Risk Statement:** Ambiguous service descriptions, unclear deliverables, unrealistic service levels, or inadequately reviewed contractual templates may lead to client disputes or obligations that the company cannot meet.

**Mitigation Actions:**

- Prepare the five approved commercial and legal templates: Proposal, SOW, NDA, MSA, and SLA.
- Obtain the required legal review before using templates in client engagements.
- Define service scope, assumptions, exclusions, deliverables, payment terms, and acceptance criteria clearly.
- Define measurable SLA commitments only where the company has the capability and resources to meet them.
- Require appropriate internal approval before committing to non-standard commercial or service terms.
- Document relevant client-specific variations.

**Risk Trigger / Early Warning:** Unclear scope statements, conflicting contractual clauses, unrealistic response-time commitments, or unresolved legal review comments.

**Risk Owner:** Lead Project Manager.

**Supporting Roles:** External Legal Adviser and Project Sponsor.

**Target:** Required templates reviewed before formal proposals or contractual commitments rely on them.

**Residual Risk:** To be reassessed after legal review and approval.

### RSK-006 — Connectivity and Service Performance

**Initial Exposure:** 2 × 3 = 6 (Low)

**Risk Statement:** Internet connectivity, network performance, or website response times at intended operating locations may affect access to operational systems or the public-facing website.

**Mitigation Actions:**

- Test the required services from the intended operating locations.
- Verify website availability, responsiveness, and basic performance before launch.
- Select hosting and CDN options where technically justified and cost-effective.
- Document practical fallback arrangements for critical connectivity needs.
- Avoid implementing redundant ISP links or complex network infrastructure unless business requirements justify the expense.

**Risk Trigger / Early Warning:** Repeated access failures, unacceptable response times, service availability problems, or failed functional checks.

**Risk Owner:** Lead Software & Cloud Engineer.

**Supporting Roles:** Lead Project Manager and relevant service providers.

**Target:** Connectivity checks completed before launch and repeated if material changes occur.

**Residual Risk:** To be reassessed after testing.

### RSK-007 — Personal Data Protection and Regulatory Compliance

**Initial Exposure:** 3 × 5 = 15 (High)

**Risk Statement:** The project may fail to identify or implement applicable personal data protection requirements affecting website inquiries, business contacts, client records, cloud processing, or commercial outreach.

**Mitigation Actions:**

- Obtain a qualified review of applicable Omani personal data protection requirements, including Royal Decree 6/2022 as amended by Royal Decree 68/2026 and the applicable executive regulations.
- Identify the categories of personal data collected, the purposes of processing, and the systems or providers handling that data.
- Determine applicable requirements for notices, consent, lawful processing, retention, deletion, and data subject requests.
- Review third-party cloud processing arrangements and any relevant cross-border data processing considerations.
- Review requirements for commercial marketing communications before dispatching client outreach.
- Restrict access to customer information and document appropriate retention and deletion procedures.
- Avoid collecting unnecessary personal data during the initial launch.

**Risk Trigger / Early Warning:** Personal data collection begins before the required review, uncertain processing permissions, missing privacy information, or unresolved legal advice concerning cloud or marketing activities.

**Risk Owner:** Lead Project Manager.

**Supporting Roles:** External Legal Adviser and Lead Software & Cloud Engineer.

**Target:** Applicable requirements assessed before relevant personal data processing or commercial outreach begins.

**Escalation:** Immediate escalation to the Project Sponsor if a material compliance gap or potential violation is identified.

**Residual Risk:** To be reassessed after legal review and implementation of required controls.

### RSK-008 — Cybersecurity and Credential Exposure

**Initial Exposure:** 3 × 5 = 15 (High)

**Risk Statement:** Unauthorized access, exposed credentials, inadequate permissions, insecure configurations, or data loss may compromise company information or disrupt operational services.

**Mitigation Actions:**

- Keep administrative accounts, business assets, and repositories under organizational control.
- Enable MFA wherever supported, particularly for privileged accounts.
- Apply least-privilege access and remove unnecessary permissions.
- Use a secure credential manager and approved secret storage.
- Never commit passwords, API keys, private keys, access tokens, or other secrets to GitHub.
- Restrict repository and cloud administration privileges to authorized personnel.
- Configure backups and verify that recovery procedures work.
- Perform basic security and configuration checks before production launch.
- Revoke access promptly when contractors or contributors no longer need it.

**Risk Trigger / Early Warning:** Exposed credentials, unexpected administrative activity, failed access-control tests, unpatched critical vulnerabilities, or unverified backups.

**Risk Owner:** Lead Software & Cloud Engineer.

**Supporting Roles:** Lead Project Manager.

**Target:** Baseline controls verified before production launch; access and backup arrangements reviewed regularly.

**Escalation:** Immediately escalate suspected material security incidents or significant exposure of sensitive information.

**Residual Risk:** To be reassessed after controls are implemented and verified.

### RSK-009 — Contractor Dependency and Asset Ownership

**Initial Exposure:** 3 × 4 = 12 (Medium)

**Risk Statement:** Dependence on individual contractors, unclear ownership arrangements, or incomplete handover may prevent the organization from maintaining its website, infrastructure, repositories, or operating documentation independently.

**Mitigation Actions:**

- Use organization-controlled accounts for critical services and repositories.
- Document ownership and transfer requirements in contractor agreements.
- Define obligations for delivery of source code, technical documentation, configuration records, and relevant work products.
- Address confidentiality and intellectual property rights in the applicable agreements.
- Maintain an inventory of accounts, services, repositories, and project assets.
- Require handover documentation and verification before contractor engagement ends.
- Ensure the organization has authorized administrative access to its critical assets.

**Risk Trigger / Early Warning:** Critical assets held in personal accounts, missing source code or documentation, disputed ownership, or refusal or inability to transfer access.

**Risk Owner:** Lead Project Manager.

**Supporting Roles:** Project Sponsor, External Legal Adviser, and Lead Software & Cloud Engineer.

**Target:** Ownership and handover requirements established before contractor engagement; transfer verified before final closeout.

**Residual Risk:** To be reassessed after ownership and handover arrangements are verified.

### RSK-010 — Schedule and Approval Delays

**Initial Exposure:** 3 × 4 = 12 (Medium)

**Risk Statement:** Delays in vendor onboarding, legal review, content preparation, technical configuration, or stakeholder decisions may threaten the planned eight-calendar-week delivery schedule.

**Mitigation Actions:**

- Confirm the project start date, target completion date, and milestone baseline.
- Identify dependencies and critical approval points in the project schedule.
- Assign an owner and target date to each material dependency.
- Agree on expected review and decision turnaround times with stakeholders.
- Review schedule progress and outstanding decisions weekly.
- Escalate delayed decisions when they threaten a milestone.
- Prepare proportionate recovery options, including resequencing work where feasible.
- Obtain formal approval for material changes to the schedule baseline.

**Risk Trigger / Early Warning:** A milestone forecast slips, a critical dependency remains unresolved, or a required approval exceeds its agreed turnaround time.

**Risk Owner:** Lead Project Manager.

**Supporting Roles:** Project Sponsor and relevant delivery contributors.

**Target:** Schedule baseline confirmed at initiation; monitoring continues throughout the project.

**Residual Risk:** To be reassessed during weekly reviews.

### RSK-011 — Initial Market Response

**Initial Exposure:** 3 × 3 = 9 (Medium)

**Risk Statement:** Target SME clients may show limited interest in the initial service portfolio, reducing the effectiveness of the project's initial outreach effort.

**Mitigation Actions:**

- Identify target SME clients whose needs align with the verified service portfolio.
- Ensure that proposals use clear service descriptions, deliverables, assumptions, and commercial terms.
- Record each proposal's dispatch date, recipient, reference, and follow-up status.
- Establish a proportionate follow-up process.
- Review responses and use feedback to refine future proposals.
- Distinguish the project's outreach completion target from commercial conversion or revenue targets.

**Risk Trigger / Early Warning:** Low engagement, repeated requests for clarification, unsuitable prospects, or no meaningful response following the agreed follow-up period.

**Risk Owner:** Marketing Lead.

**Supporting Roles:** Lead Project Manager.

**Target:** Five formal proposals dispatched by the approved final project milestone.

**Residual Risk:** To be reassessed based on actual outreach results.

---

## 5. Risk Monitoring and Governance

### 5.1 Review Frequency

The Lead Project Manager will review the Risk Register at least weekly as part of the project status review.

High risks and risks with material changes in probability or impact must receive additional attention when required.

A review must also be initiated when:

- A risk trigger occurs.
- A material scope, schedule, or budget change is proposed.
- A legal or regulatory requirement is identified or changes.
- A security or data incident is suspected.
- A major dependency becomes unavailable.
- A mitigation action fails or is overdue.

### 5.2 Escalation Criteria

A risk must be escalated to the Project Sponsor when:

- Its initial or updated score is 15 or higher.
- Its potential impact exceeds the Lead Project Manager's delegated authority.
- It threatens a critical milestone or approved budget baseline.
- It presents a material legal, regulatory, privacy, or cybersecurity concern.
- A major mitigation decision requires additional funding, a scope change, or executive authorization.

Material security incidents and possible serious compliance violations must be reported promptly and must not be delayed merely because a formal risk score has not yet been calculated.

All escalations and resulting decisions must be recorded.

### 5.3 Risk Status Definitions

| Status | Meaning |
|---|---|
| Open | Risk identified and recorded; further action or monitoring is required. |
| In Progress | Mitigation activities are underway. |
| Monitoring | Controls have been implemented and the remaining exposure is being monitored. |
| Closed | The risk is no longer applicable, has been resolved, or has been formally accepted and closed by the authorized decision-maker. |

A risk must not be marked Closed solely because the planned mitigation action has been completed.

### 5.4 Residual Risk Assessment

Residual risk is the remaining exposure after mitigation controls have been implemented and their effectiveness assessed.

Residual probability, impact, and score must be recorded during subsequent reviews when sufficient evidence is available.

Until the effectiveness of a mitigation has been verified, the initial score remains the documented baseline for that risk.

Where residual risk remains High, the Project Sponsor must decide whether further treatment, schedule or scope changes, or formal risk acceptance is appropriate.

### 5.5 Risk Action Tracking

The Lead Project Manager must maintain action records for material mitigation activities.

| Field | Requirement |
|---|---|
| Risk ID | Reference to the corresponding entry in the Risk Log |
| Action Description | Specific mitigation or corrective action |
| Action Owner | Person responsible for completing the action |
| Target Date | Agreed completion date |
| Action Status | Not Started, In Progress, Blocked, or Completed |
| Evidence | Link to the relevant test, approval, document, or other evidence |
| Residual Assessment | Updated assessment after implementation, where appropriate |

Actions must be specific, verifiable, and proportionate to the risk exposure.

---

## 6. Alignment with Project Genesis

This Risk Register supports Project Charter GEN-CH-001 and must remain consistent with the approved project baseline.

The following controls apply:

- Scope-related decisions must follow the project's change-control process.
- Budget risks must be assessed against the authorized cost baseline.
- Schedule risks must be assessed against the approved milestone plan.
- Technical risks must be assessed against the selected architecture and acceptance criteria.
- Legal and regulatory risks must be reviewed with the appropriate qualified adviser.
- Project closure must include a final risk review, outstanding-risk handover, and documented acceptance of any residual risks requiring ongoing monitoring.

Where this register conflicts with the approved Project Charter, the Lead Project Manager must identify the inconsistency and obtain a documented decision from the Project Sponsor.

---

## 7. Assumptions and Limitations

- The initial probability and impact ratings are preliminary professional estimates, not measurements derived from historical incident data.
- All risk owners must be confirmed against the actual project organization and delegated responsibilities.
- The provisional budget remains subject to confirmation of contractor costs, legal expenses, subscriptions, and other applicable charges.
- The applicability of Omani laws, licensing requirements, and personal data protection obligations must be verified by the appropriate adviser or authority.
- The Risk Register does not constitute legal advice or a certification of regulatory compliance.
- The register must be updated when material project conditions change.

### Information Security Note

This file may be maintained in a GitHub repository, subject to the organization's repository access and security policies.

Do not include passwords, API keys, private keys, access tokens, sensitive personal data, or unnecessary confidential registration information in this document.

Where detailed evidence contains confidential information, store it in an appropriately access-controlled location and reference it from the Risk Register only where permitted.

---

## 8. Document Control and Approval

### 8.1 Approval Record

| Role | Name | Approval Reference | Date |
|---|---|---|---|
| Project Sponsor | To be confirmed | To be recorded | To be confirmed |
| Lead Project Manager | Masoud | To be recorded | To be confirmed |

### 8.2 Change History

| Version | Date | Author | Description | Approval Status |
|---|---|---|---|---|
| 1.0 | 25 October 2026 | Lead Project Manager | Consolidated risk register with updated risk methodology, revised ratings, and expanded technical, security, regulatory, and delivery risks. | Pending Approval |

### 8.3 Approval Statement

This Risk Register becomes the formally approved project risk baseline only when the authorized Project Sponsor or delegate has recorded approval.

Approval of this document does not eliminate the need for ongoing monitoring, mitigation, escalation, or periodic reassessment.

**Current Document Status:** Pending Approval

---

## 9. Reference Sources

1. Project Management Institute (PMI), *A Guide to the Project Management Body of Knowledge (PMBOK® Guide) — Eighth Edition* (2025):  
   https://www.pmi.org/standards/pmbok

2. Sultanate of Oman, Royal Decree 6/2022, Personal Data Protection Law, as amended by Royal Decree 68/2026.

3. Oman Ministry of Transport, Communications and Information Technology (MTCIT), Royal Decree 68/2026 — Amending Some Provisions of the Personal Data Protection Law:  
   https://www.mtcit.gov.om/library-3/legislations-policies-8/laws-75/royal-decree-68-2026-amending-some-provisions-of-the-personal-data-protection-law-1481

4. Oman Ministerial Decision 34/2024, Executive Regulation of the Personal Data Protection Law. Its applicability and interaction with subsequent amendments must be confirmed during legal review.

---

> **End of Document**
