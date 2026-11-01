# Governance

This document defines the operating standards for the Vane Enterprise LLC GitHub organization and all repositories under its umbrella.

## Purpose

The organization’s technical operating model must balance speed with accountability. This governance model establishes the minimum standards required to maintain secure, traceable, and professional engineering practices.

## Core Principles

1. Security first
2. Clear ownership
3. Protected collaboration
4. Documentation discipline
5. Sustainable delivery

## Required Repository Controls

Every repository should maintain:

- a clear purpose and README
- explicit owners and maintainers
- protected default branch
- issue and PR templates
- review requirement for non-trivial changes
- status checks before merge
- dependency and secret monitoring

## Review and Approval Policy

- All changes to protected branches must go through a pull request.
- At least one approval is required for normal changes.
- Security-sensitive changes require additional review and explicit approval.
- Reviews must be addressed and resolved before merge.

## Branch Protection Expectations

Protected branches should enforce:

- required pull request reviews
- required status checks
- dismissal of stale reviews
- no force pushes
- no direct pushes to the default branch

## Access Model

- Organization owners hold authority for governance and repository lifecycle decisions.
- Repository maintainers manage day-to-day review, quality, and operational health.
- Contributors should operate with least privilege and be reviewed for elevated access.

## Security Policy Alignment

The organization should align repository governance to the security and disclosure standards described in SECURITY.md. Security incidents should be handled privately and responsibly.

## Exceptions

Exceptions to these standards must be documented, justified, and reviewed by an authorized owner. Exceptions should be time-bound and re-evaluated periodically.

---

This governance model is intended to preserve trust, enforce accountability, and support long-term maintainability across the organization’s technical footprint.
