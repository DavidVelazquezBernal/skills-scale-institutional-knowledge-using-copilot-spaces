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

## Technical Leads / Delivery Leads

### Role Summary
Technical Leads / Delivery Leads align technical execution with delivery commitments. They guide implementation choices, coordinate dependencies, and help the team translate roadmap goals into an achievable delivery plan.

### Responsibilities
- Shape solution direction, architecture decisions, and implementation sequencing
- Coordinate engineering dependencies, technical risks, and integration points
- Support estimation, delivery planning, and trade-off discussions
- Keep delivery quality, maintainability, and operational readiness visible

### Goals
- Deliver solutions that are technically sound and practical to ship
- Reduce delivery risk caused by unclear design or unmanaged dependencies
- Help the team sustain predictable execution across iterations

### Typical Communication
- Daily collaboration with Developers on design, blockers, and delivery risks
- Working sessions with Product Managers on scope and trade-offs
- Ongoing coordination with Project Managers on dependencies, sequencing, and escalations
- Technical updates for Stakeholders when decisions affect timelines or outcomes

### Interaction with Existing Roles
- **Developers:** clarify implementation direction, review trade-offs, and unblock technical decisions
- **Product Managers:** align scope with feasibility, sequencing, and outcome expectations
- **Project Managers:** surface delivery risks, dependencies, and timeline impacts early
- **Stakeholders:** explain major technical constraints, options, and delivery implications in business terms

---

## QA / Quality Owners

### Role Summary
QA / Quality Owners ensure that quality expectations are explicit and validated before release. They help the team define test coverage, acceptance readiness, and release confidence.

### Responsibilities
- Define and coordinate test strategy, acceptance validation, and quality checks
- Track defects, quality risks, and readiness criteria through execution
- Confirm critical workflows are validated before release
- Help improve quality practices through retrospectives and defect analysis

### Goals
- Prevent avoidable defects from reaching production
- Improve release confidence and shared understanding of quality standards
- Make quality risks visible early enough to act on them

### Typical Communication
- Daily coordination with Developers on defects, testability, and validation gaps
- Clarification with Product Managers on acceptance criteria and expected behavior
- Status updates with Project Managers on quality risks and release readiness
- Readiness summaries for Stakeholders before major milestones or launches

### Interaction with Existing Roles
- **Developers:** partner on testability, defect triage, and root-cause follow-up
- **Product Managers:** confirm acceptance criteria and edge-case expectations
- **Project Managers:** report quality risks, defect trends, and readiness status
- **Stakeholders:** communicate release confidence, major quality concerns, and validation outcomes

---

## Release Managers / Change Coordinators

### Role Summary
Release Managers / Change Coordinators own the operational coordination needed to move work safely into production. They connect readiness checks, deployment timing, communications, and contingency planning.

### Responsibilities
- Coordinate release schedules, deployment checkpoints, and go/no-go decisions
- Ensure release notes, rollback plans, and communication steps are prepared
- Track operational dependencies across teams involved in a release
- Confirm post-release verification and follow-up actions are completed

### Goals
- Reduce release risk and avoid preventable deployment surprises
- Keep releases predictable, well-communicated, and easy to support
- Improve operational readiness across planning, launch, and follow-through

### Typical Communication
- Release readiness check-ins with Developers and QA / Quality Owners
- Planning syncs with Product Managers on timing, scope, and launch constraints
- Coordination with Project Managers on milestones, dependencies, and stakeholder updates
- Release announcements and change windows communicated to Stakeholders and support partners

### Interaction with Existing Roles
- **Developers:** confirm deployment steps, rollback options, and post-release ownership
- **Product Managers:** align release timing with business priorities and launch expectations
- **Project Managers:** coordinate schedules, approvals, risks, and communication timing
- **Stakeholders:** provide clear release timing, impact summaries, and status updates before and after launch

---

## Sponsors / Business Owners

### Role Summary
Sponsors / Business Owners represent the business outcome, investment rationale, and decision authority behind a project. They help the team stay aligned on why the work matters and what success must look like.

### Responsibilities
- Set business priorities, success criteria, and key decisions requiring leadership approval
- Resolve escalations that affect scope, funding, timing, or organizational alignment
- Champion the project with broader leadership and partner teams
- Review progress against expected business outcomes

### Goals
- Ensure the project delivers measurable business value
- Keep decision-making timely when trade-offs or escalations arise
- Maintain alignment between delivery progress and strategic intent

### Typical Communication
- Milestone reviews with Product Managers and Project Managers
- Decision-oriented discussions with Technical Leads / Delivery Leads when trade-offs affect outcomes
- Periodic updates with Stakeholders, sponsors, and leadership groups
- Escalation handling when delivery decisions need executive direction

### Interaction with Existing Roles
- **Developers:** usually interact through demos, major milestone reviews, or escalations with delivery impact
- **Product Managers:** align on outcomes, priorities, and scope decisions
- **Project Managers:** review status, risks, and decisions requiring sponsor support
- **Stakeholders:** provide strategic alignment and decision clarity across business groups

---

## Customer Champions

### Role Summary
Customer Champions represent the customer perspective in planning, validation, and rollout activities. They help the team ground decisions in real user needs, adoption risks, and communication clarity.

### Responsibilities
- Bring customer feedback, workflow context, and adoption concerns into delivery decisions
- Validate whether planned solutions address customer needs and usability expectations
- Support launch readiness by identifying communication, enablement, or change-management needs
- Help interpret customer impact after release

### Goals
- Improve customer fit, usability, and adoption of delivered work
- Reduce the gap between internal assumptions and customer reality
- Help teams make decisions that are easier for customers to understand and adopt

### Typical Communication
- Discovery and feedback reviews with Product Managers
- Clarification with Developers and QA / Quality Owners on customer workflows and edge cases
- Coordination with Project Managers and Release Managers on enablement needs and launch messaging
- Ongoing voice-of-customer updates shared with Stakeholders

### Interaction with Existing Roles
- **Developers:** clarify customer workflows, pain points, and adoption-sensitive edge cases
- **Product Managers:** provide customer insight that informs prioritization and acceptance decisions
- **Project Managers:** flag communication and rollout needs that affect delivery planning
- **Stakeholders:** help align internal teams around customer expectations, launch readiness, and post-release feedback

---

## Role Interaction Summary

The personas above work best when ownership is explicit and handoffs stay lightweight. Product Managers define the outcome, Project Managers coordinate delivery, Technical Leads / Delivery Leads guide execution, QA / Quality Owners validate readiness, Release Managers / Change Coordinators coordinate launch, and Sponsors / Business Owners or Customer Champions keep the work aligned to business and customer value.

| Activity | Primary role | Key supporting roles |
| --- | --- | --- |
| Scope and outcome definition | Product Managers | Sponsors / Business Owners, Customer Champions, Stakeholders |
| Delivery planning and dependency management | Project Managers | Technical Leads / Delivery Leads, Developers, Product Managers |
| Technical execution decisions | Technical Leads / Delivery Leads | Developers, Product Managers, Project Managers |
| Quality strategy and acceptance readiness | QA / Quality Owners | Developers, Product Managers, Project Managers |
| Release coordination and go/no-go | Release Managers / Change Coordinators | QA / Quality Owners, Developers, Project Managers, Product Managers |
| Escalations and business trade-offs | Sponsors / Business Owners | Product Managers, Project Managers, Technical Leads / Delivery Leads |

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
