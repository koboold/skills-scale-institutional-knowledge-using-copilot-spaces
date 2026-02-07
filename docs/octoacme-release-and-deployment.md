# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

### Cross-Functional Release Coordination
- [ ] **Support Engineer**: Briefed on new features, known issues, and troubleshooting steps
- [ ] **UX Designer**: Verified UI/UX changes in staging environment
- [ ] **Change Manager**: Change approvals documented and communicated
- [ ] **SME**: Critical functionality validated in pre-production
- [ ] **Product Manager**: Release notes and customer communication approved

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - **Support Engineer**: Immediately notify affected customers and provide status updates
  - **Change Manager**: Document incident and update change records
  - Rollback to last known-good release if necessary
  - **SME**: Assist with root cause analysis if domain expertise needed
  - Triage root cause and capture action items
  - Schedule post-incident review with cross-functional team

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
