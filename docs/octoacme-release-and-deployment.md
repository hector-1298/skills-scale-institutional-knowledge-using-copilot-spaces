# OctoAcme — Release & Deployment Guide

<!-- Updated 2025-10-20: Expanded to include Release Manager and DevOps Engineer roles in release process (Issue #4) -->

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (coordinated with DevOps Engineer)
- Release notes drafted
- Rollback / mitigation plan documented (with DevOps Engineer and Release Manager)
- Smoke tests prepared
- Support documentation and runbooks ready (with Support Lead)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - coordinated by Release Manager
- [ ] Backup or snapshot (if applicable) - prepared by DevOps Engineer
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred) - executed by DevOps Engineer
- [ ] Run post-deploy verifications - monitored by DevOps Engineer
- [ ] Announce release to stakeholders and support - coordinated by Release Manager and communicated to Support Lead

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer)
  - Rollback to last known-good release if necessary (executed by DevOps Engineer, coordinated by Release Manager)
  - Triage root cause and capture action items
  - Communicate status to Support Lead for customer communication

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
