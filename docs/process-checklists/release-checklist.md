# Release Checklist

Use this checklist to prepare and execute a release. Ensure all items are completed before deploying to production.

## Pre-Release Preparation

- [ ] **Update Changelog**: Document all changes, new features, bug fixes, and breaking changes in the changelog file
- [ ] **Run Full Test Suite**: Execute all unit, integration, and end-to-end tests to ensure no regressions
- [ ] **Feature Flag Gating**: Verify that high-risk features are gated behind feature flags for controlled rollout
- [ ] **Deployment Runbook**: Review and update the deployment runbook with current procedures and rollback steps

## Deployment Phase

- [ ] **Monitoring Checks**: Confirm monitoring dashboards and alerts are configured for the new release
- [ ] **Rollback Plan**: Document and test the rollback procedure in case issues arise post-deployment
- [ ] **Stakeholder Communication**: Notify relevant stakeholders of the release schedule and expected impacts

## Post-Release

- [ ] **Update Documentation**: Ensure user-facing documentation reflects the changes in this release
- [ ] **Verify Monitoring**: Check monitoring dashboards for errors, performance issues, or anomalies
- [ ] **Collect Feedback**: Gather initial feedback from users and stakeholders on the release

## Notes

- Use this checklist for every production release
- Archive completed checklists for future reference and process improvement
- Update this template based on lessons learned from retrospectives
