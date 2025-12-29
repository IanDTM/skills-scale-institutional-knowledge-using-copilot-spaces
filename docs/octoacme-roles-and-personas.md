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

### Key Interactions
- **With Product Managers**: Collaborates on feature specifications and acceptance criteria, provides technical feasibility input, and estimates effort for roadmap planning.
- **With Project Managers**: Reports on task progress and blockers, participates in sprint planning and retrospectives, and helps identify technical risks and dependencies.
- **With UX Designers**: Reviews design specifications for technical feasibility, implements UI/UX designs, and provides feedback on design implementation challenges.
- **With DevOps Engineers**: Collaborates on CI/CD pipeline requirements, troubleshoots deployment issues, and ensures code is production-ready.

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

### Key Interactions
- **With Developers**: Defines feature requirements and acceptance criteria, reviews implementation progress, and makes trade-off decisions on scope and technical approach.
- **With Project Managers**: Aligns on roadmap priorities and timelines, communicates product vision and goals, and collaborates on stakeholder management.
- **With UX Designers**: Partners on user research and design validation, ensures designs align with product vision, and prioritizes design improvements.
- **With Customer Support/Success**: Gathers user feedback and pain points, prioritizes bug fixes and feature requests, and communicates product changes and rationale.

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

### Key Interactions
- **With Developers**: Facilitates sprint planning and retrospectives, tracks task progress and blockers, and manages dependencies and resource allocation.
- **With Product Managers**: Aligns on priorities and timelines, escalates risks and constraints, and coordinates stakeholder communication.
- **With DevOps Engineers**: Coordinates release schedules and deployment windows, tracks infrastructure dependencies, and participates in go/no-go decisions.
- **With Technical Writers**: Ensures documentation is scheduled and tracked, coordinates documentation reviews, and manages documentation as part of release deliverables.

---

## UX Designer

### Role Summary
UX Designers design the user experience and interface for products. They ensure usability, accessibility, and consistency with product vision through research, prototyping, and validation.

### Responsibilities
- Collaborate with Product Managers to understand user needs and translate them into design solutions
- Prototype and validate design concepts through wireframes, mockups, and interactive prototypes
- Conduct usability testing and advocate for user-centered solutions
- Review features with Developers to ensure feasible implementation and provide design specifications
- Maintain design systems and ensure consistency across product experiences
- Participate in design reviews and gather feedback from stakeholders

### Goals
- Create intuitive, accessible, and delightful user experiences
- Ensure design decisions are validated with user research and testing
- Maintain design consistency and quality across the product
- Reduce friction and improve user satisfaction metrics

### Typical Communication
- Design workshops and brainstorming sessions with Product Managers
- Design review sessions with Developers and Product Managers
- Usability testing debriefs with cross-functional teams
- Feedback and iteration discussions in retrospectives
- Weekly syncs with Product Managers on upcoming features

### Key Interactions
- **With Developers**: Provides detailed design specifications, reviews implementation to ensure design fidelity, and collaborates on technical constraints and feasible solutions.
- **With Product Managers**: Aligns on user needs and business goals, validates design concepts against product vision, and contributes to feature prioritization based on user research insights.
- **With Project Managers**: Participates in planning sessions to estimate design effort, reports on design milestone completion, and flags design-related dependencies or blockers.

---

## Technical Writer

### Role Summary
Technical Writers develop and maintain documentation for internal and external audiences, including user guides, API documentation, process docs, and release notes. They ensure information is accurate, accessible, and up-to-date.

### Responsibilities
- Create and maintain user-facing documentation (guides, tutorials, FAQs)
- Develop internal documentation (process docs, runbooks, onboarding materials)
- Write release notes and update notifications for product changes
- Partner with Developers and Product Managers to ensure technical accuracy
- Ensure documentation stays current with product changes and new features
- Maintain documentation standards and style guides
- Support customer onboarding and knowledge base management

### Goals
- Provide clear, accurate, and helpful documentation for all audiences
- Reduce support burden through comprehensive self-service resources
- Enable faster onboarding for new team members and customers
- Maintain high documentation quality and consistency

### Typical Communication
- Draft reviews with Engineering and Product teams for technical accuracy
- Update notifications to all-hands or release communication channels
- Collaboration sessions with Developers to understand technical details
- Feedback collection from Customer Support on common documentation gaps
- Documentation planning meetings during sprint planning

### Key Interactions
- **With Developers**: Reviews technical implementation details, validates code examples and API documentation, and collaborates on inline code comments and README files.
- **With Product Managers**: Aligns on feature messaging and user-facing language, incorporates product vision into documentation, and contributes to release communications.
- **With Project Managers**: Coordinates documentation timelines with release schedules, reports on documentation completion status, and participates in project kickoffs to understand documentation needs.
- **With Customer Support**: Gathers feedback on documentation gaps and common user questions, creates knowledge base articles for frequent issues, and updates documentation based on support insights.

---

## DevOps Engineer

### Role Summary
DevOps Engineers ensure infrastructure reliability and deployment efficiency through CI/CD pipelines, monitoring, automation, and infrastructure management. They bridge development and operations to enable smooth, rapid, and safe releases.

### Responsibilities
- Design, build, and maintain CI/CD pipelines for build, test, and deployment
- Manage infrastructure provisioning, scaling, and configuration
- Implement monitoring, alerting, and observability solutions
- Troubleshoot system issues and performance problems pre- and post-release
- Document operational procedures and runbooks
- Collaborate on incident response and conduct postmortems
- Optimize deployment processes for speed and reliability
- Ensure security best practices in infrastructure and deployment

### Goals
- Achieve fast, safe, and reliable deployments with minimal manual intervention
- Maintain high system availability and performance
- Reduce deployment-related incidents and rollback frequency
- Improve observability and reduce mean time to resolution (MTTR)

### Typical Communication
- Regular syncs with Developers and Product Managers on release plans and timelines
- Incident bridges and war rooms during production issues
- Postmortem reviews to identify and prevent recurring issues
- Infrastructure planning meetings for capacity and scaling needs
- Daily standups to report on pipeline health and infrastructure status

### Key Interactions
- **With Developers**: Collaborates on CI/CD pipeline requirements, troubleshoots build and deployment issues, provides infrastructure specifications, and reviews infrastructure-as-code changes.
- **With Product Managers**: Aligns on release schedules and deployment windows, communicates infrastructure constraints and scaling timelines, and provides input on feature feasibility from an operational perspective.
- **With Project Managers**: Reports on deployment readiness and infrastructure milestones, escalates infrastructure-related risks and dependencies, and participates in release planning and go/no-go decisions.

---

## Customer Support/Success

### Role Summary
Customer Support/Success professionals interface directly with users, gathering feedback, communicating product changes, and ensuring customer satisfaction. They serve as the voice of the customer within the organization.

### Responsibilities
- Respond to user inquiries and troubleshoot issues via support channels
- Relay user-reported issues and bugs to relevant project roles (Developers, Product Managers)
- Provide insights and feedback for product improvements based on user interactions
- Update users on release status, new features, and major changes
- Create and maintain customer-facing knowledge base articles and FAQs
- Track customer satisfaction metrics and identify trends
- Escalate critical issues and advocate for customer needs

### Goals
- Maximize customer satisfaction and retention
- Reduce average resolution time for customer issues
- Provide actionable product feedback to improve user experience
- Enable customer self-service through effective knowledge sharing

### Typical Communication
- Weekly product update meetings to stay informed on upcoming releases
- Escalation communications to Product Managers and Developers for critical issues
- Customer-facing announcements about new features and changes
- Feedback sessions with Product Managers to share user insights
- Daily triage meetings with support team to prioritize issues

### Key Interactions
- **With Developers**: Escalates bugs and technical issues with detailed reproduction steps, provides user context for troubleshooting, and validates fixes in staging environments before customer communication.
- **With Product Managers**: Shares customer feedback and feature requests, contributes to product roadmap prioritization based on user needs, and collaborates on release communications and rollout strategies.
- **With Project Managers**: Reports on customer-impacting issues that may affect project timelines, participates in release planning to prepare support resources, and provides customer impact assessments for go/no-go decisions.
- **With Technical Writers**: Collaborates on knowledge base content and user documentation, provides feedback on documentation clarity based on customer questions, and helps identify documentation gaps.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

