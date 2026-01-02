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

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather, analyze, and document requirements, ensuring that delivered solutions meet stakeholder expectations and business objectives.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate business needs into functional specifications and user stories
- Create process flows, data models, and requirement traceability matrices
- Facilitate requirements workshops and validation sessions
- Support user acceptance testing (UAT) by defining test scenarios
- Analyze business processes and recommend improvements

### Goals
- Ensure requirements are clear, complete, and testable
- Minimize rework due to unclear or changing requirements
- Enable smooth handoffs between stakeholders and development team

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and data models
- Stakeholder interviews and validation sessions
- Backlog refinement and sprint planning input

### Key Interactions / Handoffs
- **Product Owner:** Collaborates to refine product vision into detailed requirements
- **Project Manager:** Coordinates on timeline impacts of requirement changes
- **Technical Lead:** Works together to ensure technical feasibility of requirements
- **Development Team:** Provides clarification on acceptance criteria and expected behavior
- **Stakeholders:** Gathers needs and validates solutions meet expectations
- **QA Lead:** Partners to define acceptance criteria and UAT scenarios

### RACI Matrix Example

| Activity | Business Analyst | Product Owner | Project Manager | Technical Lead | Development Team | Stakeholders |
|----------|------------------|---------------|-----------------|----------------|------------------|--------------|
| Requirements Definition | R | A | C | C | C | I |
| Acceptance Criteria Creation | R | A | I | C | C | I |
| UAT Planning | R | C | C | I | I | C |
| Process Documentation | R | C | I | I | I | C |
| Requirements Validation | C | A | I | C | I | R |

### Onboarding Checklist
- [ ] Introduction to product vision and business context
- [ ] Access to requirements management tools and documentation repository
- [ ] Review existing requirements, user stories, and acceptance criteria
- [ ] Meet key stakeholders and understand their domains
- [ ] Shadow requirements gathering and refinement sessions
- [ ] Review template standards for user stories and specifications

---

## Scrum Master / Facilitator

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices. They ensure the team can work efficiently and continuously improve their processes.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and impediments to team progress
- Coach the team on agile principles and continuous improvement
- Shield the team from external interruptions and distractions
- Track team metrics (velocity, burndown, cycle time)
- Foster a culture of collaboration, transparency, and accountability

### Goals
- Maximize team productivity and flow
- Ensure agile practices are followed effectively
- Create a safe environment for experimentation and learning

### Typical Communication
- Facilitate team ceremonies and discussions
- Impediment logs and resolution tracking
- Team health metrics and improvement actions
- One-on-one coaching conversations

### Key Interactions / Handoffs
- **Development Team:** Coaches and supports daily work, removes blockers
- **Product Owner:** Ensures backlog is ready and priorities are clear
- **Project Manager:** Coordinates on resource needs and cross-team dependencies
- **Technical Lead:** Partners on technical process improvements
- **Stakeholders:** Communicates team capacity and shields team from disruptions

### RACI Matrix Example

| Activity | Scrum Master | Product Owner | Project Manager | Technical Lead | Development Team | Stakeholders |
|----------|--------------|---------------|-----------------|----------------|------------------|--------------|
| Sprint Planning Facilitation | R/A | C | I | C | C | I |
| Daily Standup Facilitation | R/A | I | I | C | C | I |
| Retrospective Facilitation | R/A | C | I | C | C | I |
| Impediment Removal | R/A | C | C | C | C | I |
| Process Improvement | R | C | C | C | C | I |

### Onboarding Checklist
- [ ] Review team charter, working agreements, and Definition of Done
- [ ] Understand current sprint cadence and ceremony schedule
- [ ] Access to project boards, metrics dashboards, and retrospective notes
- [ ] Meet team members and understand team dynamics
- [ ] Shadow existing ceremonies to observe team interactions
- [ ] Review impediment log and learn escalation paths

---

## Stakeholder Champion

### Role Summary
Stakeholder Champions represent and advocate for specific stakeholder groups or business units. They ensure stakeholder needs are understood, prioritized appropriately, and that stakeholders are informed of progress and changes.

### Responsibilities
- Represent stakeholder interests in planning and prioritization discussions
- Communicate project status, changes, and impacts to stakeholder groups
- Gather feedback and validate that delivered solutions meet stakeholder needs
- Escalate issues and concerns that affect stakeholder commitments
- Facilitate stakeholder engagement and buy-in for project decisions
- Balance competing stakeholder priorities and advocate for fair trade-offs

### Goals
- Ensure stakeholder voices are heard and considered
- Maintain stakeholder satisfaction and engagement
- Minimize surprises and manage stakeholder expectations

### Typical Communication
- Stakeholder briefings and status updates
- Feedback collection sessions and surveys
- Change impact assessments and communication plans
- Escalation of critical concerns to leadership

### Key Interactions / Handoffs
- **Stakeholders:** Primary liaison, gathering needs and communicating updates
- **Product Owner:** Provides stakeholder input for prioritization decisions
- **Project Manager:** Coordinates on communication plans and milestone updates
- **Business Analyst:** Partners to ensure stakeholder requirements are captured
- **Change Manager:** Collaborates on stakeholder readiness and adoption

### RACI Matrix Example

| Activity | Stakeholder Champion | Product Owner | Project Manager | Business Analyst | Development Team | Stakeholders |
|----------|----------------------|---------------|-----------------|------------------|------------------|--------------|
| Stakeholder Communication | R/A | C | C | I | I | I |
| Feedback Collection | R/A | C | I | C | I | R |
| Change Impact Assessment | R | C | C | C | I | C |
| Stakeholder Prioritization Input | R | A | I | C | I | C |
| Acceptance Sign-off | C | C | I | I | I | A |

### Onboarding Checklist
- [ ] Introduction to all stakeholder groups and their interests
- [ ] Review communication plan and stakeholder engagement strategy
- [ ] Access to stakeholder contact lists and communication channels
- [ ] Understand project objectives and how they affect stakeholders
- [ ] Review previous stakeholder feedback and concerns
- [ ] Schedule initial meetings with key stakeholder representatives

---

## Change Manager

### Role Summary
Change Managers plan and execute organizational change initiatives, ensuring smooth adoption of new processes, tools, or ways of working. They minimize resistance and maximize user readiness and engagement.

### Responsibilities
- Assess change impact and readiness across affected groups
- Develop change management and communication strategies
- Create training materials and conduct user training sessions
- Identify and work with change champions and early adopters
- Monitor adoption metrics and address resistance or barriers
- Coordinate transition activities and cutover planning

### Goals
- Achieve high adoption rates and minimize disruption
- Reduce resistance and increase user engagement
- Ensure users are prepared and confident with changes

### Typical Communication
- Change impact assessments and readiness reports
- Training materials, guides, and FAQs
- Communication plans and stakeholder updates
- Adoption metrics and feedback summaries

### Key Interactions / Handoffs
- **Stakeholder Champion:** Partners to engage stakeholders and gather feedback
- **Project Manager:** Coordinates on timeline and cutover planning
- **Product Owner:** Ensures change activities align with product rollout
- **QA Lead:** Coordinates on UAT and training environment setup
- **Stakeholders:** Communicates changes and provides training and support

### RACI Matrix Example

| Activity | Change Manager | Project Manager | Product Owner | Stakeholder Champion | QA Lead | Stakeholders |
|----------|----------------|-----------------|---------------|----------------------|---------|--------------|
| Change Impact Assessment | R/A | C | C | C | I | I |
| Training Development | R/A | I | C | C | C | I |
| Communication Planning | R | C | C | C | I | I |
| Adoption Monitoring | R/A | C | I | C | I | I |
| Resistance Management | R/A | C | C | C | I | C |

### Onboarding Checklist
- [ ] Understand the scope and nature of changes being introduced
- [ ] Review stakeholder analysis and impact assessment
- [ ] Access to communication tools and training platforms
- [ ] Meet change champions and early adopters
- [ ] Review previous change initiatives and lessons learned
- [ ] Develop initial communication and training plan draft

---

## Quality Assurance Lead

### Role Summary
QA Leads define and oversee quality strategy, testing processes, and acceptance criteria. They ensure deliverables meet quality standards and coordinate testing activities across the team.

### Responsibilities
- Define quality standards, test strategy, and acceptance criteria
- Plan and coordinate testing activities (unit, integration, UAT, regression)
- Review test coverage and identify gaps or risks
- Lead defect triage and prioritization
- Coordinate user acceptance testing with stakeholders
- Track quality metrics (defect density, test coverage, escape rate)

### Goals
- Deliver high-quality, reliable software
- Catch defects early and minimize production issues
- Establish clear quality gates and Definition of Done

### Typical Communication
- Test plans, test cases, and quality reports
- Defect logs and triage meeting notes
- Quality metrics dashboards and trend analysis
- UAT coordination with stakeholders and business analysts

### Key Interactions / Handoffs
- **Development Team:** Collaborates on testing approach and defect resolution
- **Business Analyst:** Partners to define testable acceptance criteria
- **Technical Lead:** Coordinates on test automation strategy and environments
- **Product Owner:** Validates quality gates align with product expectations
- **Project Manager:** Reports on testing progress and quality risks
- **Stakeholders:** Facilitates UAT and gathers feedback on quality

### RACI Matrix Example

| Activity | QA Lead | Development Team | Technical Lead | Business Analyst | Product Owner | Stakeholders |
|----------|---------|------------------|----------------|------------------|---------------|--------------|
| Test Strategy Definition | R/A | C | C | C | C | I |
| Acceptance Testing | R | C | C | C | A | C |
| Defect Triage | R/A | C | C | I | C | I |
| Test Automation | C | R | A | I | I | I |
| Release Approval | C | I | C | I | A | I |

### Onboarding Checklist
- [ ] Review quality standards and Definition of Done
- [ ] Access to test management tools and defect tracking systems
- [ ] Understand current test coverage and automation strategy
- [ ] Meet with development team to discuss testing processes
- [ ] Review existing test plans and test case documentation
- [ ] Shadow UAT sessions and defect triage meetings

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

