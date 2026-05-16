# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (Proposed)

To improve clarity, accountability, and cross-functional collaboration, consider adding the following personas. Each section below includes a concise role summary, responsibilities, and how the role typically interacts with existing roles.

### Technical Program Manager (TPM)
Role summary: TPMs focus on cross-team technical delivery, coordinating dependencies across multiple engineering teams and ensuring that technical milestones align with product goals.

Responsibilities:
- Drive cross-team planning and unblock inter-team dependencies
- Translate product goals into coordinated technical milestones
- Track end-to-end delivery timelines and risks
- Facilitate technical decision-making and trade-offs

Interactions with existing roles:
- Works closely with Project Managers on schedules and risk registers
- Partners with Product Managers to align technical plans with product priorities
- Coordinates with Engineers and Architects to sequence work and define interfaces

Why add: TPMs reduce handoff friction on complex initiatives and improve predictability for cross-team delivery.

---

### Release / Deployment Manager
Role summary: Owns release coordination, deployment safety, and rollback procedures across staging and production environments.

Responsibilities:
- Coordinate release windows and deployment runbooks
- Validate pre-release checklists (CI, security scans, smoke tests)
- Ensure rollback plans and incident contacts are current
- Communicate release scope and status to stakeholders

Interactions:
- Collaborates with DevOps/SRE for deployment automation
- Works with PMs and Product to schedule releases and communicate impacts
- Coordinates with QA for staging verification and smoke testing

Why add: Clarifies ownership for release safety and reduces production risk.

---

### DevOps / Site Reliability Engineer (SRE)
Role summary: Focuses on reliability, scalability, observability, and operational readiness of the system.

Responsibilities:
- Build and maintain CI/CD pipelines and infrastructure as code
- Implement monitoring, alerting, and on-call practices
- Lead incident response and post-incident analysis
- Optimize system performance and cost

Interactions:
- Partners with Developers to make systems production-ready
- Works with Release Manager to automate deployments and run pre-release checks
- Provides metrics and dashboards used by PMs and Product for KPI monitoring

Why add: Offers clear ownership for operational readiness and reliability engineering practices.

---

### UX Researcher / Product Designer
Role summary: Owns user research, interaction design, and ensures designs meet accessibility and usability goals.

Responsibilities:
- Conduct user research and usability testing
- Produce wireframes, prototypes, and design specs
- Define UX acceptance criteria and accessibility requirements
- Collaborate on A/B tests and experiments

Interactions:
- Works with Product Managers to validate solutions and success metrics
- Partners with Developers to clarify UI requirements and acceptance criteria
- Shares insights with PM and stakeholders to inform prioritization

Why add: Strengthens user-centered design and reduces rework due to unclear UX requirements.

---

### Data Analyst / Product Analyst
Role summary: Provides data-driven insights, defines measurement plans, and helps interpret success metrics.

Responsibilities:
- Define event and metric taxonomy for experiments and features
- Produce dashboards and periodic analyses to guide decisions
- Validate success criteria and measure outcomes post-release

Interactions:
- Works with Product Managers to define measurable success metrics
- Provides Developers and QA with instrumentation requirements
- Shares findings with stakeholders to influence roadmap decisions

Why add: Ensures decisions are grounded in data and that success metrics are measurable and actionable.

---

### Security / Compliance Lead
Role summary: Ensures security, privacy, and regulatory requirements are identified and addressed throughout the project lifecycle.

Responsibilities:
- Review designs and architectures for security risks
- Define compliance checkpoints and required approvals
- Coordinate security scans, threat modeling, and audits

Interactions:
- Advises Product and Engineering during planning and design
- Works with DevOps/SRE on secure deployments and secrets management
- Escalates potential compliance blockers to PM and Product

Why add: Prevents late-stage security and compliance surprises and defines an explicit review path.

---

### Customer Success / Support Lead
Role summary: Represents customer operations and post-release support requirements.

Responsibilities:
- Define support-level expectations and runbooks
- Capture common customer issues and feedback
- Prepare knowledge-base articles and support playbooks

Interactions:
- Feeds customer pain points to Product Managers and PMs
- Coordinates with Release Manager on support readiness for new releases
- Works with DevOps/SRE on incident triage and communications

Why add: Ensures customer impact is considered pre-release and support burden is minimized.

---

### Business Analyst / Analyst
Role summary: Translates business requirements into clear, testable acceptance criteria and helps quantify return-on-investment for features.

Responsibilities:
- Elicit detailed business requirements and use cases
- Define acceptance criteria and data needs
- Help prioritize backlog items based on business impact

Interactions:
- Partners with Product Managers and PMs to refine scope
- Works with Developers and QA to clarify acceptance criteria
- Collaborates with Data Analysts to define measurement plans

Why add: Reduces ambiguity in requirements and improves alignment between business goals and delivered functionality.

---

## Guidance for adding personas to project docs
- Keep each persona entry concise: Role summary (1–2 lines), responsibilities (bulleted), and interactions (who they work with and why).
- Map each persona to common artifacts they influence (e.g., release notes, runbooks, acceptance criteria, dashboards).
- During project initiation, list mandatory personas for the initiative and optional participants.
- Update the Project One-pager to call out required personas and owners for the first milestone.

## Example: How to use these in an initiative
- For a cross-team platform migration, the TPM, SRE, Security Lead, and Release Manager should be explicitly assigned during initiation.
- For a UX-driven feature, include Product Designer and UX Researcher in planning and acceptance criteria.

## Recommended next steps
- Add these personas to docs/octoacme-roles-and-personas.md (this update)
- Create a checklist in the Project One-pager template to identify required personas at initiation
- Run a short workshop with PM, PdM, and Tech Leads to validate the list for your org

---
