# OctoAcme — Cross-Functional Collaboration Checklist

Use this checklist to ensure that all relevant personas are identified and included throughout the project lifecycle. Review it at the start of initiation and again during planning to confirm that coverage is in place.

---

## Persona Involvement Checklist

### UX Designer
- [ ] Project has user-facing interfaces or changes to existing user flows
- [ ] UX Designer identified and confirmed for this project
- [ ] Design review sessions scheduled with Developers and Product Manager
- [ ] Accessibility requirements documented
- [ ] Usability validation planned before release

### Technical Writer
- [ ] Project introduces new APIs, workflows, or user-facing features
- [ ] Technical Writer identified and confirmed for this project
- [ ] Documentation scope agreed with Product Manager
- [ ] Documentation tasks added to backlog and release timeline
- [ ] Review sessions scheduled with Developers for accuracy checks

### Customer Support Liaison
- [ ] Project has significant customer impact or is driven by known support issues
- [ ] Customer Support Liaison identified and confirmed for this project
- [ ] Customer feedback log reviewed and shared with Product Manager
- [ ] Support team briefed on upcoming changes
- [ ] Post-release customer impact validation planned

### Data Analyst
- [ ] Project requires success metrics, instrumentation, or outcome measurement
- [ ] Data Analyst identified and confirmed for this project
- [ ] Success metrics and KPIs defined with Product Manager
- [ ] Data instrumentation requirements documented and included in backlog
- [ ] Post-release analysis and reporting approach agreed

### Security Lead
- [ ] Project involves authentication, authorization, sensitive data, or security-relevant functionality
- [ ] Security Lead identified and confirmed for this project
- [ ] Security requirements documented during initiation
- [ ] Threat modeling or security review scheduled before implementation
- [ ] Security scanning integrated into CI/CD pipeline (coordinate with Automation Engineer)
- [ ] Pre-release security sign-off planned

### Change Manager
- [ ] Project involves changes that affect external users, dependent systems, or regulated processes
- [ ] Change Manager identified and confirmed for this project
- [ ] Change request documentation requirements understood and assigned
- [ ] Rollback plan reviewed and approved before release
- [ ] Stakeholder communication for the change planned and scheduled

### Legal/Compliance Advisor
- [ ] Project involves personal data, regulated industries, third-party contracts, or new external-facing policies
- [ ] Legal/Compliance Advisor identified and confirmed for this project
- [ ] Applicable regulations and contractual obligations identified during initiation
- [ ] Compliance review milestone added to the project plan
- [ ] User-facing policies (privacy notices, terms of service) reviewed before release

### Automation Engineer
- [ ] Project introduces new services, significant infrastructure changes, or new deployment targets
- [ ] Automation Engineer identified and confirmed for this project
- [ ] CI/CD pipeline requirements reviewed and updated for the project
- [ ] Automated test and security scan coverage confirmed for new functionality
- [ ] Deployment automation tested in staging before production release

---

## Common Scenario Interaction Patterns

### Scenario: New User-Facing Feature
| Phase | Who is Involved | Key Interaction |
|---|---|---|
| Initiation | Product Manager, UX Designer | Define user needs and initial design direction |
| Planning | UX Designer, Developer, Technical Writer | Finalize designs, scope documentation tasks |
| Execution | UX Designer, Developer | Review implementation against design specs |
| Release | Technical Writer, Customer Support Liaison | Publish documentation, prepare support team |
| Close | Data Analyst, Product Manager | Measure adoption and user feedback against success metrics |

### Scenario: Bug Fix or Support-Driven Improvement
| Phase | Who is Involved | Key Interaction |
|---|---|---|
| Initiation | Customer Support Liaison, Product Manager | Escalate issue severity and customer impact |
| Planning | Developer, Project Manager | Scope fix, set timeline, assess risk |
| Execution | Developer, Customer Support Liaison | Validate fix addresses reported customer issue |
| Release | Technical Writer, Customer Support Liaison | Update documentation if needed, brief support team |
| Close | Data Analyst | Confirm reduction in related support tickets |

### Scenario: API or Infrastructure Change
| Phase | Who is Involved | Key Interaction |
|---|---|---|
| Initiation | Developer, Product Manager, Project Manager | Identify scope, impact, and need for documentation |
| Planning | Developer, Technical Writer | Document API changes and migration guides |
| Execution | Developer, Technical Writer | Review and update technical documentation |
| Release | Technical Writer, Customer Support Liaison | Publish updated docs, communicate breaking changes |
| Close | Data Analyst | Validate adoption of updated APIs through usage data |

### Scenario: Security or Compliance-Driven Change
| Phase | Who is Involved | Key Interaction |
|---|---|---|
| Initiation | Security Lead, Legal/Compliance Advisor, Product Manager | Identify regulatory requirements, security risks, and compliance obligations |
| Planning | Security Lead, Automation Engineer, Project Manager | Scope security controls, integrate scanning into pipelines, add compliance milestones |
| Execution | Security Lead, Developers, Automation Engineer | Review implementations for security issues; verify automated checks pass |
| Release | Change Manager, Legal/Compliance Advisor, Technical Writer | Obtain change approvals, confirm compliance sign-off, update policies if needed |
| Close | Data Analyst, Security Lead | Validate security metrics; confirm no outstanding compliance items |

### Scenario: Process or Infrastructure Change
| Phase | Who is Involved | Key Interaction |
|---|---|---|
| Initiation | Change Manager, Project Manager, Developer | Assess impact on dependent teams and systems, initiate change request |
| Planning | Change Manager, Automation Engineer, Project Manager | Define rollback plan, update deployment automation, communicate to stakeholders |
| Execution | Automation Engineer, Developer | Implement infrastructure changes with automated validation |
| Release | Change Manager, Customer Support Liaison | Notify affected stakeholders, brief support team |
| Close | Data Analyst, Project Manager | Confirm successful change; close change record |

---

## References
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Risk Register Template](octoacme-risk-register-template.md)
- [Stakeholder Communication Plan Template](octoacme-stakeholder-communication-plan-template.md)
