# Project Schedule Baseline — Project Genesis

| Document Metadata | Details |
|---|---|
| **Document ID** | GEN-SCH-001 |
| **Project Name** | Project Genesis — Enterprise Operational Infrastructure & Service Workflows Launch |
| **Document Type** | Project Schedule Baseline |
| **Project Location** | Bousher and Barka, Sultanate of Oman |
| **Primary Learning Resource** | Google Project Management Professional Certificate (Coursera) |
| **Project Management Approach** | Hybrid Project Management — structured governance combined with iterative and Agile delivery practices |
| **Document Owner** | Lead Project Manager |
| **Version** | 1.0 |
| **Status** | Draft — Review Pending |
| **Last Updated** | 6 November 2026 |
| **Planned Duration** | 8 Calendar Weeks (Nominally 40 Business Days) |
| **Planned Start Date** | To be confirmed |
| **Target Completion Date** | To be confirmed |
| **Related Documents** | `01-initiation/project-charter.md` (GEN-CH-001); `01-initiation/stakeholder-register.md` (GEN-STK-001); `02-planning/scope-baseline.md` (GEN-SBL-001); `02-planning/risk-register.md` (GEN-RSK-001); `02-planning/communication-management-plan.md` (GEN-COM-001) |

---

## 1. Purpose and Schedule Objectives

### 1.1 Purpose

This document establishes the planned schedule framework for Project Genesis, translating the approved Work Breakdown Structure (WBS) into a time-based delivery plan.

It defines the planned activity sequence, estimated durations, dependencies, resource responsibilities, milestone targets, and preliminary critical path considerations required to coordinate and control project execution.

The Schedule Baseline will serve as the reference point for monitoring schedule performance, evaluating delays, coordinating resources, and assessing the impact of proposed changes.

### 1.2 Schedule Objectives

The objectives of this schedule are to:

- Translate the WBS work packages into an executable activity schedule.
- Define logical activity sequencing and dependencies.
- Estimate the duration required for each work package.
- Assign activity ownership in alignment with the Stakeholder Register and RACI Matrix.
- Establish milestone targets across the eight-week delivery window.
- Identify activities that may run in parallel.
- Identify potential critical-path activities and schedule constraints.
- Provide a measurable basis for tracking progress and forecast completion.
- Establish procedures for monitoring schedule deviations and approving baseline changes.

### 1.3 Schedule Baseline Principle

The schedule must remain consistent with the approved Scope Baseline (GEN-SBL-001).

Every scheduled activity must be traceable to a corresponding WBS code or an explicitly authorized project management activity.

The schedule does not authorize additional scope, expenditure, or resource commitments beyond the approved project baseline and delegated authority.

---

## 2. Schedule Basis and Planning Assumptions

### 2.1 Planned Project Duration

The initial project duration is eight calendar weeks.

For planning purposes, this is equivalent to approximately 40 business days, assuming a five-day working week.

The actual working-day calendar must be confirmed against the organization's operating calendar in Oman, taking applicable weekends, public holidays, and contributor availability into consideration.

The planned start and completion dates will be established after the project schedule and relevant planning baselines have received the required approval.

### 2.2 Schedule Assumptions

The schedule is based on the following assumptions:

- The Project Charter and Scope Baseline will receive the required authorization before baseline-dependent execution begins.
- Key stakeholders and designated contributors will be available during their assigned work periods.
- The Project Sponsor will provide required decisions within agreed review periods.
- External legal review will be available during the planned documentation review window.
- Required domain, hosting, cloud, and SaaS services will be available within reasonable provisioning periods.
- Corporate registration information and approved business content will be available for verification.
- Technical and marketing activities can be performed in parallel where dependencies permit.
- Contractor responsibilities and availability will be confirmed before the relevant work packages are scheduled for execution.
- Material regulatory and security dependencies will be addressed before the affected production activities begin.

### 2.3 Duration Estimation Approach

Initial work-package durations are planning estimates.

They are based on the anticipated task complexity, scope, dependencies, and the proposed resource model.

The estimates must be reviewed and validated by the relevant activity owners before the schedule is formally approved.

The following methods may be used where appropriate:

- Expert judgment.
- Analogous estimation based on comparable activities.
- Bottom-up estimation for decomposed work packages.
- Three-point estimation where significant duration uncertainty exists.

No historical project performance data is currently assumed to be available.

The initial estimates must therefore not be treated as measured historical productivity or guaranteed completion times.

### 2.4 Schedule Constraints

The principal schedule constraints are:

- Eight-calendar-week planned execution window.
- Limited availability of specialist contractors.
- External legal and regulatory review dependencies.
- Domain registration and third-party provisioning requirements.
- Approval dependencies for commercial and legal documents.
- The approved project scope and financial envelope.

Any forecast delay that threatens the project completion date must be assessed and escalated through project governance.

---

## 3. Activity Definition and Sequencing

### 3.1 Activity Identification

Project activities are derived from the lowest-level work packages in the Scope Baseline (GEN-SBL-001).

Each scheduled activity retains its original WBS code to support traceability between scope definition, responsibility assignment, and schedule monitoring.

### 3.2 Dependency Types

The following dependency types may be used in the detailed schedule:

| Dependency Type | Description |
|---|---|
| Finish-to-Start (FS) | The successor activity cannot begin until the predecessor activity is completed. |
| Start-to-Start (SS) | The successor activity may begin once the predecessor has started and the required conditions are satisfied. |
| Finish-to-Finish (FF) | The successor activity cannot finish until the predecessor activity has finished. |
| External Dependency | The activity depends on a third party, vendor, regulator, or other party outside the immediate project team's control. |

Finish-to-Start is the default dependency used in the preliminary schedule unless another logical relationship is explicitly justified.

### 3.3 Parallel Activities

Where dependencies permit, technical, administrative, legal, and marketing activities may be executed concurrently.

Examples include:

- Stakeholder identification and initial risk assessment.
- Domain provisioning and commercial template drafting.
- Asana workspace configuration and GitHub repository setup.
- Website development and legal template preparation.
- Service catalogue content preparation and SOP documentation.

Parallel execution must not compromise quality, regulatory requirements, resource availability, or formal approval controls.

---

## 4. Detailed Activity Schedule

The following schedule translates the 28 lowest-level WBS work packages into estimated durations, dependencies, and planned delivery windows.

All durations are expressed in business days.

The predecessor column identifies logical dependencies. Some activities may overlap within the same target week when their resource and approval requirements permit.

### 4.1 Initiation and Planning Baseline

| WBS Code | Activity | Duration | Planned Window | Predecessor(s) | Responsible Role | Accountable Owner |
|---|---|---:|---|---|---|---|
| **1.1.1** | Project Charter & Authorization | 2 days | Week 1 | None | Lead PM | Project Sponsor |
| **1.1.2** | Stakeholder Register & RACI | 2 days | Week 1 | 1.1.1 (initial authorization) | Lead PM | Project Sponsor |
| **1.1.3** | Initial Risk Register | 2 days | Weeks 1–2 | 1.1.1, 1.1.2 | Lead PM | Lead PM |
| **1.1.4** | Scope, Schedule & Cost Baseline Review and Approval | 2 days | Week 2 | 1.1.1, 1.1.2, 1.1.3; draft planning documents available | Lead PM | Project Sponsor |

**Planning Note:** Draft planning documents are prepared before the baseline approval activity. Early preparatory work may proceed in parallel only where separately authorized and within delegated authority.

### 4.2 Digital Infrastructure Foundation — D1

| WBS Code | Activity | Duration | Planned Window | Predecessor(s) | Responsible Role | Accountable Owner |
|---|---|---:|---|---|---|---|
| **1.2.1** | Corporate Domain & DNS Provisioning | 5 days | Weeks 1–2 | 1.1.1; relevant registration and domain eligibility information | Lead Software & Cloud Engineer | Lead PM |
| **1.2.2** | Corporate Workspace & Email Setup | 3 days | Week 2 | 1.2.1 | Lead Software & Cloud Engineer | Lead PM |
| **1.2.3** | Identity, Access & Security Controls | 2 days | Week 2 | 1.2.2 | Lead Software & Cloud Engineer | Lead PM |

### 4.3 Corporate Web Presence — D2

| WBS Code | Activity | Duration | Planned Window | Predecessor(s) | Responsible Role | Accountable Owner |
|---|---|---:|---|---|---|---|
| **1.3.1** | Bilingual Content & Brand Preparation | 5 days | Weeks 2–3 | 1.6.1; approved corporate information and brand inputs | Marketing Lead | Lead PM |
| **1.3.2** | Website Implementation & Hosting | 10 days | Weeks 3–5 | 1.2.1, 1.3.1 | Lead Software & Cloud Engineer | Lead PM |
| **1.3.3** | Production Website Release | 1 day | Week 6 | 1.3.4 | Lead Software & Cloud Engineer | Lead PM |
| **1.3.4** | Website Quality & Security Testing | 3 days | Week 6 | 1.3.2 | Lead Software & Cloud Engineer | Lead PM |

**Sequencing Note:** Website testing must be completed before the final production release. The WBS numbering identifies work packages but does not override their logical execution sequence.

### 4.4 Commercial and Legal Template Suite — D3

| WBS Code | Activity | Duration | Planned Window | Predecessor(s) | Responsible Role | Accountable Owner |
|---|---|---:|---|---|---|---|
| **1.4.1** | SOW & NDA Templates | 3 days | Weeks 2–3 | 1.1.1; approved business requirements | Lead PM | Lead PM |
| **1.4.2** | MSA & SLA Templates | 3 days | Weeks 3–4 | 1.4.1 | Lead PM | Lead PM |
| **1.4.3** | Commercial Proposal Template | 2 days | Weeks 3–4 | 1.4.1; approved commercial inputs | Marketing Lead | Lead PM |
| **1.4.4** | External Legal Review | 5 days | Week 4 | 1.4.1, 1.4.2, 1.4.3 | External Legal Adviser | Lead PM |

Legal review duration is a provisional estimate and depends on the availability of the external adviser and the complexity of review comments.

### 4.5 Operational Workspace and Workflows — D4

| WBS Code | Activity | Duration | Planned Window | Predecessor(s) | Responsible Role | Accountable Owner |
|---|---|---:|---|---|---|---|
| **1.5.1** | Asana Workspace Configuration | 3 days | Weeks 2–3 | 1.1.2 | Lead PM | Lead PM |
| **1.5.2** | SOP & Operational Checklist Development | 4 days | Weeks 3–4 | 1.5.1, 1.6.1 | Lead PM | Lead PM |
| **1.5.3** | GitHub Repository & Secret Management Controls | 2 days | Week 2 | 1.1.1 | Lead Software & Cloud Engineer | Lead PM |

### 4.6 Digital Service Catalogue — D5

| WBS Code | Activity | Duration | Planned Window | Predecessor(s) | Responsible Role | Accountable Owner |
|---|---|---:|---|---|---|---|
| **1.6.1** | CR Activity Verification & Service Mapping | 2 days | Weeks 1–2 | 1.1.1; official CR information available | Lead PM | Lead PM |
| **1.6.2** | Service Catalogue Content Preparation | 4 days | Weeks 4–5 | 1.6.1, 1.3.1; approved service and commercial inputs | Marketing Lead | Lead PM |
| **1.6.3** | Service Catalogue Publication | 1 day | Week 6 | 1.6.2, 1.3.3 | Marketing Lead | Lead PM |

### 4.7 Client Outreach Package — D6

| WBS Code | Activity | Duration | Planned Window | Predecessor(s) | Responsible Role | Accountable Owner |
|---|---|---:|---|---|---|---|
| **1.7.1** | SME Prospect Identification & Qualification | 3 days | Weeks 6–7 | 1.6.1, preliminary service portfolio information | Marketing Lead | Lead PM |
| **1.7.2** | Proposal Customization | 3 days | Weeks 7–8 | 1.4.4, 1.6.2, 1.7.1 | Marketing Lead | Lead PM |
| **1.7.3** | Proposal Dispatch & Outreach Register | 1 day | Week 8 | 1.7.2; required commercial authorization and applicable marketing compliance checks | Marketing Lead | Lead PM |

### 4.8 Project Closeout Package — D7

| WBS Code | Activity | Duration | Planned Window | Predecessor(s) | Responsible Role | Accountable Owner |
|---|---|---:|---|---|---|---|
| **1.8.1** | Deliverable Acceptance Review | 2 days | Week 8 | Completion and evidence for D1–D6 | Lead PM | Project Sponsor |
| **1.8.2** | Asset Handover & Outstanding Actions | 2 days | Week 8 | Relevant technical and operational deliverables completed | Relevant Asset Owners, coordinated by Lead PM | Lead PM |
| **1.8.3** | Lessons Learned Retrospective | 1 day | Week 8 | Major project delivery activities substantially completed | Lead PM | Lead PM |
| **1.8.4** | Closeout Report & Sponsor Sign-Off | 2 days | Week 8 | 1.8.1, 1.8.2, 1.8.3 | Lead PM | Project Sponsor |

---

## 5. High-Level Weekly Schedule

The following table summarizes the planned distribution of major activities across the eight-week project window.

| Week | Main Activities | Expected Outputs |
|---|---|---|
| **Week 1** | Project authorization, stakeholder identification, initial risk assessment, CR activity verification, domain provisioning initiation. | Initial governance and project setup activities initiated. |
| **Week 2** | Planning baseline review, cloud workspace and email setup, MFA and access controls, GitHub and Asana configuration, initial contract drafting, bilingual content preparation. | Digital infrastructure foundation and planning controls progressing. |
| **Week 3** | Website development, commercial and legal template preparation, Asana workflow configuration, SOP development, service catalogue preparation. | Core technical, legal, and operational work packages underway. |
| **Week 4** | Continued website development, external legal review, SOP completion, service catalogue content preparation. | Legal review completed or material comments documented; operational workflows prepared. |
| **Week 5** | Website implementation completion, final service catalogue content review, technical preparation for production testing. | Website ready for formal testing; catalogue content ready for publication review. |
| **Week 6** | Website quality and security testing, production website release, service catalogue publication, initial SME prospect qualification. | Bilingual website and service catalogue launched; outreach preparation underway. |
| **Week 7** | SME prospect qualification, proposal customization, commercial review and approval coordination. | Customized proposals prepared for qualified prospects. |
| **Week 8** | Dispatch of five proposals, deliverable acceptance, technical and operational handover, lessons learned, and project closure. | Project closeout package and sponsor sign-off. |

Activities may overlap where their dependencies and resource requirements permit.

The weekly schedule is a planning view and does not replace the detailed WBS-based activity schedule.

---

## 6. Project Milestones

Milestones represent significant events or completion points in the project lifecycle.

Unlike work-package activities, milestones have zero planned duration.

| Milestone ID | Milestone Description | Target Window | Completion Evidence |
|---|---|---|---|
| **M1** | Project Authorization & Planning Baseline | Week 2 | Approved Project Charter and required planning baselines. |
| **M2** | Digital Infrastructure Foundation | Weeks 1–2 | Verified domain, corporate email, cloud workspace, and baseline security configuration. |
| **M3** | Commercial and Legal Template Review | Weeks 3–4 | Five templates prepared and required legal and business review recorded. |
| **M4** | Operational Workspace Ready | Weeks 2–4 | Asana workspace, operational workflows, SOPs, and repository controls reviewed. |
| **M5** | Corporate Website and Service Catalogue Launch | Weeks 5–6 | Bilingual website and approved service catalogue published. |
| **M6** | Client Outreach Completed | Week 8 | Five formal proposals dispatched and evidence recorded. |
| **M7** | Project Closure | Week 8 | Deliverable acceptance, handover, Closeout Report, and Sponsor approval. |

Milestone completion requires documented evidence. A target week alone does not constitute milestone acceptance.

---

## 7. Schedule Dependencies and Critical Path Analysis

### 7.1 Key Schedule Dependencies

The following dependencies are considered particularly important to successful delivery.

| Dependency ID | Predecessor | Successor | Dependency Description |
|---|---|---|---|
| DEP-01 | Project Authorization (1.1.1) | Baseline-dependent execution activities | Formal authorization is required before work proceeds beyond permitted initiation activities. |
| DEP-02 | CR Activity Verification (1.6.1) | Service Catalogue and public business content | Commercial activity descriptions must be verified before definitive service claims are published. |
| DEP-03 | Domain and DNS Provisioning (1.2.1) | Website Hosting and Deployment (1.3.2) | The selected domain and required DNS configuration must be available for deployment. |
| DEP-04 | Corporate Workspace Setup (1.2.2) | Identity and Access Controls (1.2.3) | Relevant user and administrative accounts must be provisioned before access controls are fully verified. |
| DEP-05 | Bilingual Content Preparation (1.3.1) | Website Implementation (1.3.2) | Approved content and brand inputs are required for website development. |
| DEP-06 | Website Implementation (1.3.2) | Website Testing (1.3.4) | The implemented website must be available for functional and security testing. |
| DEP-07 | Website Testing (1.3.4) | Production Release (1.3.3) | Final production publication depends on successful completion of required testing. |
| DEP-08 | Legal Template Review (1.4.4) | Proposal Customization (1.7.2) | Required commercial and legal review must be completed before proposals rely on the approved templates. |
| DEP-09 | Service Catalogue Preparation (1.6.2) | Service Catalogue Publication (1.6.3) | Approved service content must be available before publication. |
| DEP-10 | Proposal Customization (1.7.2) | Proposal Dispatch (1.7.3) | Proposals must be finalized and authorized before dispatch. |
| DEP-11 | Deliverable Completion (D1–D6) | Acceptance Review (1.8.1) | Completion evidence must be available before formal acceptance. |
| DEP-12 | Acceptance and Handover (1.8.1, 1.8.2) | Final Closeout (1.8.4) | Required acceptance and handover records must be completed before formal closure. |

### 7.2 Preliminary Critical Path Considerations

The following activity chains are considered potential critical-path candidates based on the current scope, dependencies, and planned delivery windows.

**Website and Service Launch Path:**

```text
Project Authorization
        |
        v
CR Activity Verification
        |
        v
Bilingual Content Preparation
        |
        v
Website Implementation & Hosting
        |
        v
Website Quality & Security Testing
        |
        v
Production Website Release
        |
        v
Service Catalogue Publication
```

**Commercial Outreach Path:**

```text
Commercial Template Preparation
        |
        v
External Legal Review
        |
        v
Service Catalogue Approval
        |
        v
SME Prospect Qualification
        |
        v
Proposal Customization
        |
        v
Proposal Dispatch
```

**Project Closure Path:**

```text
Completion of D1–D6
        |
        v
Deliverable Acceptance Review
        |
        v
Asset Handover and Lessons Learned
        |
        v
Closeout Report
        |
        v
Project Sponsor Sign-Off
```

These paths highlight activities whose delays may affect the overall completion date.

**Critical Path Status:** Preliminary — Not Formally Validated.

A fully validated Critical Path Method (CPM) calculation requires:

- Confirmed activity durations.
- Finalized dependency relationships.
- A confirmed working-day calendar.
- Resource availability and allocation.
- Identification of mandatory and flexible dependencies.
- Calculation of early start, early finish, late start, late finish, and total float.

Until these inputs are confirmed, the identified chains must be treated as critical-path candidates rather than a formally calculated critical path.

### 7.3 Schedule Buffer and Contingency

The eight-week delivery target is the initial planning constraint.

The detailed schedule must identify activities with high uncertainty, particularly:

- Domain registration and DNS provisioning.
- External legal review.
- Website implementation and technical testing.
- Stakeholder approval turnaround times.
- Client proposal preparation and authorization.

Any time reserve must be explicitly identified and approved as part of the final schedule baseline.

Unallocated time must not automatically be treated as available capacity for additional scope.

---

## 8. Resource and Responsibility Assignment

Schedule ownership must remain consistent with the Stakeholder Register and RACI Matrix (GEN-STK-001).

The following roles are assigned at the planning level:

| Role | Schedule Responsibility |
|---|---|
| Project Sponsor | Approves the schedule baseline and material schedule changes. |
| Lead Project Manager | Develops and maintains the schedule, coordinates dependencies, tracks progress, and escalates forecast delays. |
| Lead Software & Cloud Engineer | Estimates and executes technical work packages, validates technical dependencies, and reports implementation progress. |
| Marketing Lead | Estimates and executes content, catalogue, and client outreach activities. |
| External Legal Adviser | Performs assigned legal review and communicates review findings within the agreed engagement. |
| Authorized Company Signatory | Provides required business and commercial approvals before commitments are made. |
| Data Protection Officer | Supports relevant privacy and data protection reviews where applicable. |
| Database Administrator | Performs assigned database work if required by the approved technical architecture. |

### 8.1 Resource Availability

The schedule assumes that assigned contributors will be available during their planned activity windows.

Actual availability, contractual working arrangements, and potential resource conflicts must be confirmed before final approval.

No individual resource capacity is assumed beyond the assignments and availability formally agreed with the relevant contributors.

### 8.2 Resource Conflicts

If a contributor is assigned to overlapping activities that cannot reasonably be performed in parallel, the Lead Project Manager must:

- Review task priorities and dependencies.
- Identify alternative sequencing options.
- Assess schedule and cost impacts.
- Reassign work only within authorized resource arrangements.
- Submit material changes for Project Sponsor approval where required.

---

## 9. Schedule Monitoring and Control

### 9.1 Progress Tracking

The Lead Project Manager will monitor schedule performance throughout project execution.

Progress will be tracked using:

- WBS activity completion.
- Actual start and finish dates.
- Forecast completion dates.
- Milestone achievement.
- Outstanding dependencies.
- Overdue tasks.
- Resource availability.
- Approved and pending change requests.

Asana will be used for operational task tracking, while the controlled project repository will retain the approved schedule baseline and relevant governance records.

### 9.2 Schedule Reporting

Schedule status will be included in the weekly project status report.

Reports should identify:

- Planned versus actual progress.
- Milestones completed and upcoming.
- Forecast schedule deviations.
- Critical dependencies and blockers.
- Activities at risk of delay.
- Required corrective actions.
- Decisions requiring Sponsor intervention.

### 9.3 Schedule Variance and Escalation

The following thresholds align with the Project Communication Management Plan (GEN-COM-001).

| Condition | Required Response |
|---|---|
| Minor deviation within the agreed activity duration | Task Owner monitors and corrects as appropriate. |
| Forecast delay exceeding two business days or threatening a milestone | Lead PM assesses the impact and initiates corrective action. |
| Forecast delay exceeding five business days or threatening the project completion date | Escalate to the Project Sponsor with a recovery or change recommendation. |
| Material dependency or external approval delay | Escalate according to impact and urgency. |
| Schedule change affecting the approved completion date or baseline | Formal Change Request and Sponsor approval required. |

These thresholds are management triggers and must not be treated as permission to ignore material schedule risks below the stated values.

### 9.4 Schedule Change Control

Any material change affecting the approved schedule baseline must be documented through the project Change Request process.

The Lead Project Manager will assess:

- Activity duration changes.
- Dependency changes.
- Milestone impacts.
- Resource availability.
- Cost implications.
- Quality and compliance consequences.
- Impact on the final project completion date.

Material baseline changes require Project Sponsor approval before implementation.

Approved changes must be recorded in the Change Log and incorporated into the controlled schedule document.

### 9.5 Schedule Baseline Updates

The original approved schedule baseline must remain identifiable for performance comparison.

Revisions must be version-controlled and must include:

- Revision date.
- Reason for change.
- Description of affected activities or milestones.
- Schedule impact assessment.
- Approval reference.
- Updated baseline version where authorized.

The schedule baseline must not be silently overwritten when actual progress differs from the original plan.

---

## 10. Schedule Risks and Constraints

The following risks may materially influence the planned completion date.

| Risk Reference | Schedule Risk | Potential Impact | Management Response |
|---|---|---|---|
| RSK-001 | Cloud architecture or configuration delays | Delayed technical readiness and website deployment | Confirm the target architecture early and validate access and provisioning requirements. |
| RSK-002 | Commercial registration or regulatory clarification delays | Delayed service verification and public-facing claims | Initiate verification early and engage the appropriate adviser. |
| RSK-003 | Scope creep | Increased workload and schedule slippage | Enforce formal change control. |
| RSK-005 | Contractual or service definition issues | Delayed legal approval and commercial proposal preparation | Conduct early business and legal review. |
| RSK-007 | Personal data protection compliance gaps | Delayed website forms or client outreach | Complete relevant privacy review before affected processing activities begin. |
| RSK-008 | Cybersecurity or credential exposure | Service disruption, investigation, and recovery delays | Implement baseline security controls and maintain incident response arrangements. |
| RSK-010 | Approval and dependency delays | Threat to planned milestones and project completion | Track decision deadlines and escalate outstanding approvals. |
| RSK-011 | Weak initial client engagement | Reduced effectiveness of the outreach campaign | Qualify suitable prospects and prepare targeted proposals. |

Risk owners remain responsible for reporting material changes in risk exposure to the Lead Project Manager.

---

## 11. Schedule Performance and Completion Criteria

Project Genesis will be considered schedule-complete when:

- The approved project deliverables have reached their documented completion and acceptance stages.
- The agreed milestone requirements have been satisfied or formally approved exceptions have been recorded.
- Five formal client proposals have been dispatched and their evidence retained.
- Technical and operational handover requirements have been completed.
- Outstanding schedule-related issues have been assigned owners and follow-up dates.
- The Project Closeout Report has been prepared.
- The Project Sponsor or authorized delegate has formally approved project closure.

The planned eight-week duration is a target, not a guarantee of commercial, operational, or regulatory outcomes.

Any decision to extend or revise the duration must follow the schedule change-control process.

---

## 12. Document Control and Approval

### 12.1 Approval Record

| Role | Name | Approval Action | Date |
|---|---|---|---|
| Project Sponsor | To be confirmed | Pending Approval | To be recorded |
| Lead Project Manager | Masoud | Prepared and Submitted for Review | 6 November 2026 |

### 12.2 Revision History

| Version | Date | Author | Description of Change | Status |
|---|---|---|---|---|
| 1.0 | 6 November 2026 | Lead Project Manager | Initial Schedule Baseline document, including activity sequencing, duration estimates, resource assignments, milestone plan, preliminary critical path considerations, and schedule control procedures. | Draft — Review Pending |

### 12.3 Approval Statement

This document becomes the approved Project Schedule Baseline only after the Project Sponsor or formally authorized delegate has recorded approval.

Until approval is recorded, the schedule remains a proposed planning baseline and must not be treated as independent authorization to incur expenditure or undertake work beyond existing delegated authority.

Material changes to the approved schedule must follow the project's change-control procedure.

---

## 13. Reference Resources

### 13.1 Primary Learning Resource

**Google Project Management Professional Certificate — Coursera**

https://www.coursera.org/professional-certificates/google-project-management

Educational resource informing practical scheduling, activity sequencing, estimation, dependency management, and project coordination methods.

### 13.2 Related Project Documents

1. Project Charter — GEN-CH-001.  
   `01-initiation/project-charter.md`

2. Stakeholder Register & RACI Matrix — GEN-STK-001.  
   `01-initiation/stakeholder-register.md`

3. Scope Baseline — GEN-SBL-001.  
   `02-planning/scope-baseline.md`

4. Risk Register — GEN-RSK-001.  
   `02-planning/risk-register.md`

5. Communication Management Plan — GEN-COM-001.  
   `02-planning/communication-management-plan.md`

---

**End of Document**
