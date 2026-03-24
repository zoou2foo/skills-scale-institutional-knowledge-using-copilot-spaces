# OctoAcme — Definition of Done Template

Use this template to define and agree on the criteria that must be met before a backlog item, feature, or release is considered complete. Fill in or adjust each section to match your project's requirements before sprint planning begins.

---

## Project / Feature Name
_[Enter the name of the project or feature this DoD applies to]_

## Version / Sprint
_[Enter the sprint number or release version]_

## Last Updated
_[Date]_

## Approver(s)
_[List the roles or individuals who must sign off that the DoD is met]_

---

## Functional Completeness

- [ ] All acceptance criteria defined in the backlog item are met
- [ ] Feature behaves correctly in all defined user scenarios
- [ ] Edge cases and error paths have been considered and handled
- [ ] No known regressions introduced in existing functionality

---

## Code Quality

- [ ] Code reviewed and approved by at least one peer
- [ ] Code follows agreed naming conventions and style guidelines
- [ ] No critical or high-severity static analysis / linting issues
- [ ] Technical debt introduced is documented and added to the backlog

---

## Testing

- [ ] Unit tests written and passing for new or changed logic
- [ ] Integration tests updated or created as applicable
- [ ] End-to-end / acceptance tests passing for affected user flows
- [ ] Test coverage meets the agreed threshold for this project
- [ ] Exploratory or manual testing completed where automated coverage is insufficient

---

## Security

- [ ] Security review completed (if feature involves authentication, authorization, or sensitive data)
- [ ] No new high or critical vulnerabilities introduced (as verified by automated scanning)
- [ ] Sensitive data is handled according to the data handling policy

---

## Documentation

- [ ] Inline code comments updated where logic is complex or non-obvious
- [ ] User-facing documentation updated (user guides, release notes) if feature affects end users
- [ ] API documentation updated if public or internal APIs changed
- [ ] Architecture or design decisions documented if significant changes were made

---

## Accessibility & UX

- [ ] Feature meets agreed accessibility standards (e.g., WCAG 2.1 AA)
- [ ] UX Designer has reviewed the implementation against design specifications
- [ ] Responsive behavior verified on supported screen sizes / devices (if applicable)

---

## Deployment Readiness

- [ ] Feature is deployable to staging / pre-production environment
- [ ] Feature flags / rollout configuration set correctly (if applicable)
- [ ] Database migrations or schema changes are backward-compatible or have a rollback plan
- [ ] CI/CD pipeline passes all required stages (build, test, security scan)

---

## Stakeholder Sign-Off

- [ ] Product Manager has validated the feature against acceptance criteria
- [ ] Customer Support Liaison briefed on changes (if customer-facing)
- [ ] Any required Change Manager approval obtained (if subject to change control)

---

## Notes / Exceptions
_[Document any intentional exceptions to the above criteria and the rationale for each]_

---

## References
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Planning](octoacme-project-planning.md)
- [Risk Register Template](octoacme-risk-register-template.md)
