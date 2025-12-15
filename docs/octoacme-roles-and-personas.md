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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile principles and practices. They ensure the team follows the agreed-upon process and continuously improves delivery flow.

### Responsibilities
- Facilitate sprint ceremonies (planning, daily standups, reviews, retrospectives)
- Remove blockers and impediments preventing team progress
- Coach team members on agile practices and self-organization
- Track sprint metrics and team velocity
- Foster collaboration and resolve conflicts
- Shield the team from external interruptions

### Goals
- Maximize team productivity and delivery flow
- Maintain sustainable pace and reduce burnout
- Improve team collaboration and communication
- Increase predictability and transparency

### Typical Communication
- Daily standups with development team
- Sprint planning and retrospective facilitation
- Weekly syncs with Project Managers on delivery progress
- One-on-one coaching sessions with team members
- Escalation of persistent blockers to Project Managers

### Key Interactions
- **Developers**: Daily facilitation, removing impediments, coaching on practices
- **Project Managers**: Coordinating on delivery timelines, dependencies, and risks
- **Product Managers**: Clarifying requirements, managing backlog priorities
- **QA Lead**: Ensuring quality gates are understood and integrated into sprint flow

---

## UX Designer

### Role Summary
UX Designers create user-centered designs, conduct research, gather feedback, and ensure solutions are usable and aligned with user needs. They bridge user insights with product and engineering decisions.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define interaction patterns and information architecture
- Validate designs with users and stakeholders
- Collaborate on accessibility and inclusive design
- Maintain design systems and component libraries

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction
- Ensure design consistency across products
- Validate solutions with real user feedback

### Typical Communication
- Weekly design reviews with Product Managers
- Design critiques and collaboration sessions
- Handoff meetings with Developers on implementation details
- User research share-outs with stakeholders
- Usability test results and recommendations

### Key Interactions
- **Product Managers**: Aligning designs with product vision and priorities
- **Developers**: Handing off designs, clarifying implementation details, reviewing builds
- **QA Lead**: Defining acceptance criteria for visual and interaction quality
- **Stakeholders**: Presenting designs, gathering feedback, validating solutions

---

## QA Lead

### Role Summary
QA Leads oversee quality strategy, test coverage, and ensure features meet acceptance criteria and quality standards. They coordinate testing activities and drive quality improvements across the team.

### Responsibilities
- Define test strategy and quality gates
- Oversee test planning and execution (manual and automated)
- Triage bugs and coordinate with development on fixes
- Ensure acceptance criteria are testable and met
- Track quality metrics and test coverage
- Advocate for quality improvements and technical debt reduction

### Goals
- Maintain high product quality and reliability
- Catch defects early in the development cycle
- Reduce production incidents and customer-facing bugs
- Improve test automation coverage and efficiency

### Typical Communication
- Daily standups with development team
- Bug triage and prioritization sessions
- Weekly quality reports to Project Managers
- Test plan reviews with Product Managers
- Collaboration with Developers on testability

### Key Interactions
- **Developers**: Collaborating on testability, reviewing code for quality, triaging bugs
- **Product Managers**: Validating acceptance criteria, reporting on quality status
- **Project Managers**: Reporting quality metrics, flagging release readiness risks
- **DevOps Engineer**: Integrating automated tests into CI/CD pipelines
- **UX Designer**: Validating user experience against design specifications

---

## DevOps Engineer

### Role Summary
DevOps Engineers implement automation for builds, deployments, and monitoring. They ensure system reliability, enable continuous delivery, and provide rapid feedback loops to the development team.

### Responsibilities
- Build and maintain CI/CD pipelines
- Automate infrastructure provisioning and configuration
- Monitor system health, performance, and reliability
- Implement security practices and compliance checks
- Manage deployment processes and rollback procedures
- Provide observability tools and dashboards

### Goals
- Enable fast, reliable deployments with minimal manual intervention
- Maximize system uptime and performance
- Reduce time to detect and resolve incidents
- Improve developer productivity through automation

### Typical Communication
- Weekly syncs with development team on pipeline improvements
- Incident post-mortems and reliability reviews
- Deployment coordination with Project Managers
- Security and compliance updates with stakeholders
- On-call handoffs and escalation procedures

### Key Interactions
- **Developers**: Providing CI/CD support, reviewing infrastructure needs, troubleshooting deployments
- **QA Lead**: Integrating automated tests into pipelines, providing test environments
- **Project Managers**: Coordinating release schedules, reporting on deployment risks
- **Product Managers**: Providing production metrics and user impact data
- **Scrum Master**: Removing deployment and infrastructure blockers

---

## Role Interaction Matrix

This section clarifies how roles collaborate and hand off work during key project phases.

### Planning & Initiation
- **Product Manager → UX Designer**: Share user needs, define design scope
- **Product Manager → Project Manager**: Define project scope, timeline, resources
- **Project Manager → Scrum Master**: Align on sprint structure and ceremonies
- **UX Designer → Developers**: Present design concepts, gather technical feasibility input

### Design & Development
- **UX Designer → Product Manager**: Validate designs against requirements
- **UX Designer → Developers**: Hand off design specifications and assets
- **Developers → QA Lead**: Share feature implementation for test planning
- **Scrum Master → All Team**: Facilitate daily standups and sprint ceremonies
- **DevOps Engineer → Developers**: Provide development environments and tooling

### Testing & Quality Assurance
- **QA Lead → Developers**: Report bugs and collaborate on fixes
- **QA Lead → DevOps Engineer**: Request test environments and automation support
- **QA Lead → Product Manager**: Validate acceptance criteria are met
- **QA Lead → UX Designer**: Verify UI/UX implementation matches designs

### Release & Deployment
- **DevOps Engineer → QA Lead**: Execute automated test suites in staging
- **DevOps Engineer → Project Manager**: Confirm deployment readiness
- **Project Manager → Product Manager**: Coordinate release communications
- **DevOps Engineer → Developers**: Monitor production metrics post-deployment
- **Scrum Master → Project Manager**: Report on sprint completion and velocity

### Retrospective & Improvement
- **Scrum Master → All Team**: Facilitate retrospective, capture action items
- **Project Manager → All Stakeholders**: Share project outcomes and lessons learned
- **All Roles → Process Documentation**: Update practices based on learnings

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The Role Interaction Matrix helps clarify handoffs and collaboration points between teams.

