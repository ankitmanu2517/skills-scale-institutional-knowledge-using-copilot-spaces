# OctoAcme — QA & Release Readiness Checklist

## Purpose
Provide a standardized checklist to ensure consistent quality validation before any release. This template addresses the gap between the execution/tracking process and the release/deployment process by formalizing QA sign-off criteria.

## When to Use
- Before marking a feature as "Done" in the sprint board
- Before promoting a release candidate to production
- During sprint review to verify acceptance criteria

---

## Feature-Level QA Checklist

### Functional Validation
- [ ] All acceptance criteria verified and passing
- [ ] Edge cases identified and tested
- [ ] Error states and validation messages confirmed
- [ ] Cross-browser/cross-platform testing completed (if applicable)

### Automated Testing
- [ ] Unit tests written and passing for new logic
- [ ] Integration tests cover key interactions
- [ ] End-to-end smoke tests pass for affected critical flows
- [ ] No regressions in existing test suite

### Code Quality
- [ ] PR reviewed and approved per team policy
- [ ] No critical or high-severity static analysis findings
- [ ] Security scanning passed in CI
- [ ] Performance benchmarks within acceptable thresholds (if applicable)

### Design & Usability
- [ ] Implementation matches design specifications
- [ ] Accessibility requirements met (keyboard navigation, screen reader, contrast)
- [ ] UX/Design Lead sign-off obtained (if applicable)

---

## Release Readiness Checklist

### Pre-Release
- [ ] All planned features/fixes merged and tested
- [ ] Release notes drafted
- [ ] Risk register reviewed — no unmitigated high-impact risks
- [ ] Rollback plan documented and tested
- [ ] Stakeholders notified of release timeline

### Deployment Verification
- [ ] Deployment to staging successful
- [ ] Smoke tests pass in staging environment
- [ ] Monitoring and alerting configured for new features
- [ ] SLO/SLI dashboards updated (if applicable)

### Post-Deployment
- [ ] Production smoke tests pass
- [ ] Key metrics (error rate, latency, usage) within expected range
- [ ] Stakeholder announcement sent
- [ ] Release retrospective scheduled (if significant release)

---

## Roles & Responsibilities

| Step | Owner | Reviewer |
|------|-------|----------|
| Functional validation | QA/Test Engineer | Developer |
| Automated test coverage | Developer | QA/Test Engineer |
| Security scan review | DevOps/SRE | Technical Lead |
| Design sign-off | UX/Design Lead | Product Manager |
| Release approval | Project Manager | Product Manager + Technical Lead |
| Deployment execution | DevOps/SRE | Project Manager |

---

## Notes
- This checklist complements (not replaces) the execution checklist in `octoacme-execution-and-tracking.md` and the release steps in `octoacme-release-and-deployment.md`.
- Customize per project — not all items apply to every release.
- Track blockers in the risk register and escalate per the defined escalation path.
