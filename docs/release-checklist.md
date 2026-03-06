# OctoAcme — Release Checklist (detailed)

Use this checklist for any production release. The checklist complements the Release & Deployment Guide.

Pre-release
- [ ] All acceptance criteria met and linked to PRs
- [ ] All PRs merged into release branch; CI green
- [ ] Security and dependency scans passed
- [ ] Migration plan documented (if applicable)
- [ ] Rollback strategy confirmed and tested on staging
- [ ] Release notes drafted and reviewed
- [ ] Monitoring dashboards and alerts reviewed for changes
- [ ] Stakeholders notified of release window and expected impact

Staging
- [ ] Deploy to staging
- [ ] Run smoke tests and critical path E2E tests
- [ ] Run regression checks for high-risk areas
- [ ] SRE / Ops validate metrics and logs for anomalies

Production
- [ ] Deploy via automated pipeline
- [ ] Run post-deploy smoke tests
- [ ] Confirm SLOs / basic KPIs are stable
- [ ] Notify Support and Stakeholders of successful deploy
- [ ] Publish release notes and updates

Post-release
- [ ] Monitor key metrics for X hours (define per project)
- [ ] Run quick retrospective if issues were found
- [ ] Document any follow-ups as issues with owners and due dates