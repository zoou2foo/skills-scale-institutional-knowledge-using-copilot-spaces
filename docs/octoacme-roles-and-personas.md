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

## UX Designer

### Role Summary
UX Designers own the user experience for product features and flows. They ensure that what gets built is intuitive, accessible, and aligned with real user needs. They translate requirements into designs and validate them through usability testing.

### Responsibilities
- Design user flows, wireframes, and prototypes
- Conduct usability testing and incorporate feedback
- Define and uphold accessibility standards
- Collaborate with Product Managers to refine requirements based on user insights
- Review implemented features against design specifications

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support errors
- Ensure design consistency across the product

### Typical Communication
- Design reviews with Developers and Product Managers
- Usability test reports and findings shared with the team
- Annotated mockups and design specs in shared design tools

### Interactions with Existing Roles
- **Product Managers**: Align on user needs, prioritize UX work, and validate feature concepts with user research
- **Developers**: Provide detailed specs and review implementations for design fidelity
- **Project Managers**: Flag design dependencies and review timelines for design tasks

---

## Technical Writer

### Role Summary
Technical Writers produce and maintain documentation that helps both internal teams and end users understand and use the product effectively. They bridge the gap between complex technical details and clear, accessible language.

### Responsibilities
- Write and maintain user guides, API documentation, and release notes
- Document internal workflows, processes, and onboarding materials
- Collaborate with Developers to accurately capture technical details
- Keep documentation up to date as features change
- Establish and enforce documentation standards and templates

### Goals
- Ensure documentation is accurate, complete, and easy to use
- Reduce support requests caused by unclear or missing documentation
- Enable faster onboarding for new team members and customers

### Typical Communication
- Review sessions with Developers and Product Managers to verify accuracy
- Documentation updates aligned with release milestones
- Feedback loops with Customer Support to identify documentation gaps

### Interactions with Existing Roles
- **Developers**: Review technical content for accuracy and completeness
- **Product Managers**: Align on what user-facing documentation is needed per release
- **Project Managers**: Coordinate documentation tasks within the project timeline

---

## Customer Support Liaison

### Role Summary
Customer Support Liaisons bring the voice of the customer into the product and project process. They synthesize support feedback, escalate recurring issues, and help teams understand the real-world impact of decisions on end users.

### Responsibilities
- Collect and summarize customer feedback and support trends
- Escalate critical customer issues to Product Managers and Developers
- Participate in planning sessions to represent customer impact
- Validate that delivered features address known customer pain points
- Maintain a feedback log and share insights with the broader team

### Goals
- Ensure customer needs are represented in product and project decisions
- Reduce repeat support tickets through proactive product improvements
- Build a feedback loop between customers and internal teams

### Typical Communication
- Regular briefings to Product Managers on top support issues and trends
- Input into backlog prioritization based on customer severity
- Post-release validation reports on customer impact

### Interactions with Existing Roles
- **Product Managers**: Share customer insights to inform roadmap and prioritization decisions
- **Developers**: Clarify real-world customer impact when scoping bug fixes and improvements
- **Project Managers**: Flag customer-impacting risks and communicate release readiness to support teams

---

## Data Analyst

### Role Summary
Data Analysts define, track, and interpret the metrics that measure project and product success. They support data-informed decision-making by surfacing insights and translating data into actionable recommendations.

### Responsibilities
- Define success metrics and KPIs in collaboration with Product Managers
- Build and maintain dashboards and reporting tools
- Analyze trends and surface actionable insights for the team
- Validate that data collection is correctly implemented
- Support post-release analysis to measure outcomes against goals

### Goals
- Enable data-driven prioritization and decision-making
- Provide timely and accurate reporting to stakeholders
- Identify early signals of issues or opportunities through data

### Typical Communication
- Metric reviews during sprint reviews and planning sessions
- Dashboard updates and summary reports for stakeholders
- Ad-hoc analysis requests from Product Managers and Project Managers

### Interactions with Existing Roles
- **Product Managers**: Collaborate to define success metrics and interpret results against product goals
- **Developers**: Verify that instrumentation and data collection are implemented correctly
- **Project Managers**: Provide progress tracking data and post-project outcome reports

---

## Security Lead

### Role Summary
Security Leads own the security posture of the project. They ensure that security requirements are identified early, that features are reviewed for potential vulnerabilities, and that the team has a clear plan for incident response. They act as the bridge between engineering practices and organizational security standards.

### Responsibilities
- Define and communicate security requirements during initiation and planning
- Review feature designs and implementations for security risks
- Conduct or coordinate security reviews, threat modeling, and penetration testing
- Maintain the security risk log and escalate critical findings
- Lead incident response planning and post-incident reviews
- Ensure compliance with applicable security frameworks (e.g., SOC 2, ISO 27001)

### Goals
- Prevent security vulnerabilities from reaching production
- Establish a security-first culture within the delivery team
- Minimize the blast radius and recovery time of any security incident

### Typical Communication
- Security review sessions at design and pre-release checkpoints
- Risk register updates flagging security-specific items
- Incident response plans and post-mortems shared with leadership

### Interactions with Existing Roles
- **Developers**: Advise on secure coding practices and review pull requests for security impact
- **Product Managers**: Identify security implications of new feature proposals and roadmap items
- **Project Managers**: Escalate security risks for inclusion in the project risk register and timeline
- **Legal/Compliance Advisor**: Align on regulatory security requirements and coordinate compliance reviews
- **Automation Engineer**: Define security scanning and compliance checks to integrate into CI/CD pipelines

---

## Change Manager

### Role Summary
Change Managers coordinate the approval, communication, and documentation of process or technical changes that affect users, other teams, or downstream systems. They ensure that changes follow established control policies and that all stakeholders are informed and aligned before changes are implemented.

### Responsibilities
- Maintain the change log and enforce change control policies
- Facilitate change advisory board (CAB) meetings when required
- Assess the impact and risk of proposed changes on users and dependent systems
- Coordinate rollback plans with Developers and Project Managers
- Communicate upcoming changes to affected stakeholders in advance
- Track and close out change records after successful implementation

### Goals
- Ensure all significant changes are approved, documented, and communicated
- Minimize disruption to users and dependent teams from unplanned or poorly communicated changes
- Build trust with stakeholders through predictable and transparent change practices

### Typical Communication
- Change request submissions and approvals via the change management system
- Pre-change notifications to affected stakeholders
- Post-change implementation reports and closure notices

### Interactions with Existing Roles
- **Project Managers**: Align on scheduling, impact assessments, and escalation paths for changes
- **Developers**: Coordinate release and deployment plans to meet change control requirements
- **Customer Support Liaison**: Brief support teams on upcoming changes and potential customer impact
- **Security Lead**: Review changes for security implications before approval
- **Legal/Compliance Advisor**: Confirm that changes meet regulatory or contractual obligations

---

## Legal/Compliance Advisor

### Role Summary
Legal/Compliance Advisors ensure that project activities, product changes, and team processes comply with applicable legal, regulatory, and contractual requirements. They proactively identify risk areas and provide guidance to reduce the organization's legal exposure.

### Responsibilities
- Review feature proposals, contracts, and policy documents for legal and regulatory compliance
- Identify applicable regulations (e.g., GDPR, HIPAA, CCPA) and communicate requirements to the team
- Advise on data handling, privacy, and intellectual property considerations
- Review and approve external-facing policies and terms of service
- Flag and escalate legal risks in the project risk register
- Coordinate with external legal counsel when specialist advice is required

### Goals
- Prevent legal or regulatory violations before they occur
- Ensure the organization can demonstrate compliance with applicable standards
- Reduce legal risk exposure through proactive guidance rather than reactive remediation

### Typical Communication
- Compliance review sessions at project initiation and before major releases
- Written guidance notes on specific regulatory requirements
- Risk register entries for legal or compliance-specific risks

### Interactions with Existing Roles
- **Product Managers**: Review proposed features for data privacy and regulatory compliance implications
- **Project Managers**: Identify compliance-driven milestones or blockers in the project plan
- **Technical Writers**: Ensure user-facing documentation (privacy notices, terms of service) is accurate and compliant
- **Security Lead**: Align on security controls required to meet regulatory standards
- **Change Manager**: Confirm that proposed changes comply with contractual or regulatory obligations before approval

---

## Automation Engineer

### Role Summary
Automation Engineers design, implement, and maintain the automated pipelines and infrastructure that underpin the software delivery lifecycle. They reduce manual effort and human error by building reliable CI/CD workflows, automated testing infrastructure, and deployment tooling.

### Responsibilities
- Design, build, and maintain CI/CD pipelines for build, test, and deployment automation
- Automate repetitive operational tasks (e.g., environment provisioning, configuration management)
- Integrate automated security scanning, code quality, and compliance checks into pipelines
- Monitor pipeline health and resolve failures that block delivery
- Document automation tooling and provide guidance to Developers on pipeline usage
- Evaluate and adopt new automation tools and frameworks that improve delivery efficiency

### Goals
- Maximize delivery speed and reliability through automation
- Eliminate manual, error-prone steps in the build, test, and release process
- Provide Developers and Project Managers with fast, accurate feedback on code quality and delivery readiness

### Typical Communication
- Pipeline status reports and failure alerts surfaced to relevant team members
- Documentation on CI/CD tooling and automation standards
- Cross-functional discussions on integrating new checks (security scans, accessibility tests) into pipelines

### Interactions with Existing Roles
- **Developers**: Provide CI/CD infrastructure and guidance on automation best practices
- **Project Managers**: Surface delivery pipeline metrics and status to support project tracking and reporting
- **Security Lead**: Integrate security scanning tools into pipelines to enforce security requirements automatically
- **Change Manager**: Align automation deployment steps with change control requirements
- **Data Analyst**: Provide build and deployment metrics to support delivery performance analysis

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When scoping a new project, use the [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) to identify which personas should be involved.

