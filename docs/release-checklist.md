# Release &amp; Deployment Checklist

This checklist standardizes release activities to reduce risk and ensure readiness.

Pre-release
- [ ] Change has clear acceptance criteria and passing CI
- [ ] Release notes drafted and reviewed by Product
- [ ] Documentation (user guides, internal runbooks) updated by Technical Writer
- [ ] Security review completed for high-risk changes
- [ ] Rollout strategy defined (feature flag, canary, phased rollout)
- [ ] Monitoring and alerts configured for new metrics

Release day
- [ ] Deployment executed by DevOps/Release engineer
- [ ] Smoke tests run and passed
- [ ] Key stakeholders and Customer Success notified of release

Post-release
- [ ] Monitor errors, performance, and user feedback for defined window
- [ ] Triage and address high-priority issues
- [ ] Document post-release findings in retrospective

Use this checklist as a template to attach to releases; adjust per project needs.
