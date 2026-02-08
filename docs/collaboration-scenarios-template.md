# Collaboration Scenarios Template

This document provides templates and examples for common cross-role collaboration scenarios in OctoAcme projects. Use these scenarios to understand how different roles work together effectively.

---

## Scenario 1: Feature Discovery and Requirements Definition

### Context
A new feature idea emerges from customer feedback. The team needs to evaluate feasibility, define requirements, and plan for development.

### Participants
- Executive Sponsor
- Product Manager (Lead)
- Business Analyst
- UX Designer
- Developer
- Project Manager

### Workflow

1. **Executive Sponsor** shares strategic context and business objectives
2. **Product Manager** conducts initial prioritization and defines problem statement
3. **Business Analyst** facilitates stakeholder interviews and documents business requirements
4. **UX Designer** conducts user research and creates initial wireframes
5. **Developer** reviews technical feasibility and provides effort estimates
6. **Product Manager** and **Business Analyst** collaborate to write user stories with acceptance criteria
7. **Project Manager** incorporates into project plan and identifies dependencies
8. **Team** reviews together in backlog refinement session

### Handoffs and Communication Points
- Executive Sponsor → Product Manager: Strategic approval and business case
- Product Manager → Business Analyst: Problem statement and success criteria
- Business Analyst → UX Designer: User requirements and business constraints
- UX Designer → Developer: Design specifications and user flows
- Developer → Project Manager: Technical dependencies and timeline estimates
- Product Manager ↔ All: Final prioritization and sprint planning

---

## Scenario 2: Sprint Planning and Execution

### Context
The team is preparing for an upcoming sprint and needs to align on scope, priorities, and commitments.

### Participants
- Product Manager
- Project Manager
- Agile Coach (Facilitator)
- Developers (Team)
- QA Lead
- UX Designer

### Workflow

1. **Agile Coach** facilitates sprint planning ceremony
2. **Product Manager** presents prioritized backlog items and business value
3. **UX Designer** clarifies design requirements and shares prototypes
4. **Developers** ask clarifying questions and discuss technical approach
5. **QA Lead** reviews acceptance criteria and testing requirements
6. **Team** collectively estimates work and commits to sprint goal
7. **Project Manager** documents sprint plan and identifies risks
8. **Agile Coach** ensures the team has clarity and alignment before starting

### Daily Collaboration During Sprint
- **Daily Standup** (facilitated by Agile Coach): All team members share progress, plans, and blockers
- **Developer ↔ UX Designer**: Ad-hoc design clarifications and implementation reviews
- **Developer ↔ QA Lead**: Continuous testing feedback and bug triaging
- **Project Manager**: Tracks progress, removes blockers, escalates risks

### Sprint Review
- **Developers** demonstrate completed features
- **Product Manager** validates against acceptance criteria
- **Stakeholders** provide feedback
- **Team** discusses what to release

---

## Scenario 3: Quality Assurance and Defect Resolution

### Context
During testing, QA discovers critical defects that need to be triaged and resolved before release.

### Participants
- QA Lead (Lead)
- Developers
- Product Manager
- Project Manager
- Business Analyst

### Workflow

1. **QA Lead** identifies and documents defects with reproduction steps
2. **QA Lead** facilitates defect triage meeting
3. **Developer** provides technical analysis and root cause assessment
4. **Product Manager** prioritizes defects based on business impact
5. **Business Analyst** clarifies expected behavior from requirements perspective
6. **Developer** fixes high-priority defects
7. **QA Lead** verifies fixes and updates test cases
8. **Project Manager** adjusts timeline if needed and communicates impact to stakeholders

### Critical Path for Blockers
- **QA Lead** identifies release-blocking defect
- **Project Manager** escalates to Product Manager and Executive Sponsor if needed
- **Product Manager** makes go/no-go decision
- **Executive Sponsor** approves delay or scope change if required

---

## Scenario 4: User Experience Design Iteration

### Context
Initial design concepts need to be refined based on stakeholder feedback and technical constraints.

### Participants
- UX Designer (Lead)
- Product Manager
- Business Analyst
- Developer
- QA Lead

### Workflow

1. **UX Designer** presents initial design concepts
2. **Product Manager** provides feedback on alignment with product vision
3. **Business Analyst** validates against business requirements and user needs
4. **Developer** assesses technical feasibility and suggests alternatives
5. **UX Designer** iterates on design based on feedback
6. **QA Lead** reviews for testability and accessibility compliance
7. **UX Designer** conducts usability testing with users
8. **Team** reviews final design in design review session
9. **UX Designer** hands off final design specifications to Developer

### Feedback Loop
- Weekly design reviews with cross-functional team
- Rapid prototyping and iteration cycles
- User testing validation before finalizing designs

---

## Scenario 5: Agile Transformation and Process Improvement

### Context
The team identifies process inefficiencies and wants to improve their ways of working.

### Participants
- Agile Coach (Lead)
- Project Manager
- Developers (Team)
- Product Manager
- Executive Sponsor

### Workflow

1. **Agile Coach** facilitates retrospective to identify pain points
2. **Team** proposes improvement ideas and experiments
3. **Agile Coach** guides team in selecting high-impact improvements
4. **Project Manager** helps incorporate changes into project workflow
5. **Product Manager** ensures changes support product delivery goals
6. **Team** implements improvement as experiment for one sprint
7. **Agile Coach** measures impact using team health metrics
8. **Executive Sponsor** provides organizational support for broader adoption
9. **Team** reviews results in next retrospective and decides to continue, adjust, or stop

### Success Metrics
- Team velocity and predictability
- Cycle time and lead time
- Team satisfaction scores
- Quality metrics (defect rates, test coverage)

---

## Scenario 6: Strategic Decision and Escalation

### Context
A critical technical or business decision requires executive input and affects project scope or timeline.

### Participants
- Executive Sponsor (Decision Maker)
- Project Manager
- Product Manager
- Developer (Technical Lead)
- Business Analyst

### Workflow

1. **Project Manager** identifies issue requiring escalation (e.g., major scope change, resource constraint, timeline risk)
2. **Project Manager** gathers relevant information and impact analysis
3. **Product Manager** provides business context and trade-off options
4. **Developer** provides technical assessment and recommendations
5. **Business Analyst** clarifies business implications and stakeholder impact
6. **Project Manager** presents options to Executive Sponsor with recommendations
7. **Executive Sponsor** makes strategic decision and secures resources if needed
8. **Project Manager** communicates decision to team and stakeholders
9. **Team** adjusts plan and execution accordingly

### Escalation Triggers
- Budget overruns or resource constraints
- Major scope changes affecting timeline
- Dependencies on other teams or external parties
- Technical blockers requiring architectural decisions
- Risk of missing critical deadlines

---

## Scenario 7: Release Planning and Deployment

### Context
The team is preparing for a major release and needs to coordinate across multiple roles to ensure successful deployment.

### Participants
- Project Manager (Coordinator)
- Product Manager
- QA Lead
- Developers (Team)
- Business Analyst
- Executive Sponsor

### Workflow

1. **Product Manager** defines release goals and success criteria
2. **QA Lead** conducts release readiness assessment
3. **Business Analyst** validates final features against business requirements
4. **Developers** prepare deployment plan and runbook
5. **QA Lead** completes final regression testing and sign-off
6. **Project Manager** coordinates release communication plan
7. **Executive Sponsor** provides final approval to deploy
8. **Developers** execute deployment
9. **QA Lead** verifies post-deployment functionality
10. **Product Manager** monitors user adoption and metrics
11. **Project Manager** facilitates post-release retrospective

### Go/No-Go Decision Criteria
- All release-blocking defects resolved
- Acceptance criteria met for all features
- Deployment runbook reviewed and approved
- Rollback plan tested and documented
- Stakeholder communication completed

---

## Scenario 8: Onboarding a New Team Member

### Context
A new team member joins the project and needs to quickly become productive.

### Participants
- Project Manager (Onboarding Coordinator)
- Agile Coach
- Team Lead (role-specific)
- Existing team members

### Workflow

1. **Project Manager** assigns onboarding buddy and shares onboarding checklist
2. **Agile Coach** provides overview of team practices and agile ceremonies
3. **Role-specific Lead** (e.g., Dev Lead, QA Lead) provides technical onboarding
4. **Team** members participate in pair programming or shadowing sessions
5. **Project Manager** schedules regular check-ins during first 30 days
6. **New member** completes role-specific onboarding tasks
7. **Team** conducts 30-day retrospective with new member to gather feedback

### Key Onboarding Resources
- [Role Onboarding Checklist](./role-onboarding-checklist.md)
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [RACI Matrix](./raci-matrix-template.md)
- Project charter and current sprint plan

---

## Creating Your Own Collaboration Scenario

Use this template to document custom collaboration scenarios for your project:

### Scenario Name
[Descriptive name]

### Context
[What triggers this collaboration? What problem are we solving?]

### Participants
- [Role 1] (Lead/Facilitator)
- [Role 2]
- [Role 3]

### Workflow
1. [Step 1: Who does what]
2. [Step 2: ...]
3. [...]

### Handoffs and Communication Points
- [Role A] → [Role B]: [What is communicated/handed off]
- [...]

### Success Criteria
- [How do we know this collaboration was successful?]

### Common Challenges and Mitigations
- **Challenge**: [Description]
  - **Mitigation**: [Solution]

---

## Tips for Effective Cross-Role Collaboration

1. **Clarify ownership**: Use RACI matrix to avoid confusion about who does what
2. **Over-communicate**: Err on the side of sharing information more rather than less
3. **Document decisions**: Keep a decision log with context, options, and rationale
4. **Respect expertise**: Trust each role's domain knowledge and recommendations
5. **Provide context**: Always explain the "why" behind requests and decisions
6. **Close the loop**: Confirm receipt of handoffs and provide status updates
7. **Ask questions**: Better to clarify upfront than make incorrect assumptions
8. **Build relationships**: Invest time in understanding other roles and building trust

---

## Additional Resources

- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [RACI Matrix Template](./raci-matrix-template.md)
- [Role Onboarding Checklist](./role-onboarding-checklist.md)
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
