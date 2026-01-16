# Security Review Checklist

Use this checklist to ensure security considerations are addressed before merging code or releasing features.

## Pre-Review Phase

- [ ] **Threat Model**: Create or update the threat model for the feature or change, identifying potential attack vectors
- [ ] **Identify Security Reviewer**: Assign a Security Champion or security-focused reviewer to the change
- [ ] **Scope Definition**: Clearly define what components, data flows, and integrations are in scope for the review

## Security Analysis

- [ ] **Dependencies Scan**: Run automated dependency scanning tools to identify known vulnerabilities in third-party libraries
- [ ] **Static Analysis**: Execute static analysis security testing (SAST) tools to detect potential security issues in the code
- [ ] **Third-Party Libraries Approval**: Verify that all new third-party dependencies are approved and from trusted sources
- [ ] **Authentication & Authorization**: Review access control mechanisms to ensure proper authentication and authorization

## Review and Approval

- [ ] **Responsible Security Reviewer**: Confirm that the designated Security Champion or security expert has reviewed the changes
- [ ] **Required Approvals**: Obtain sign-off from all required security reviewers before merging
- [ ] **Security Testing**: Verify that security-focused test cases cover the identified threats

## Documentation

- [ ] **Security Notes**: Document any security assumptions, mitigations, or residual risks
- [ ] **Update Security Documentation**: Ensure security guidelines and threat models are updated to reflect the changes

## Notes

- Use this checklist for all changes that handle sensitive data, authentication, or external integrations
- Schedule reviews early in the development process to avoid last-minute security issues
- Update this template based on security incidents and lessons learned
