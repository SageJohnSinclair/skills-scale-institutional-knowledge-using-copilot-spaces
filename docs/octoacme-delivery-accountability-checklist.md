# OctoAcme - Delivery Accountability Checklist

## Purpose
Provide a repeatable checklist for cross-functional accountability from planning through release. Use this for projects that span multiple teams or have material delivery risk.

## How to Use
- Complete this checklist during planning.
- Revisit it during weekly execution syncs.
- Finalize the release section before production deployment.
- Link the completed checklist in the project board, status update, or release notes.

## Ownership Matrix (RACI-lite)

| Delivery Area | Accountable Role | Supporting Roles |
| --- | --- | --- |
| Scope and priority decisions | Product Manager | Project Manager, Engineering Manager |
| Timeline and dependency health | Project Manager + Technical Program Manager | Engineering Manager, Developers |
| Team capacity and quality standards | Engineering Manager | Developers, QA Lead |
| Test strategy and quality gates | QA Lead | Developers, Product Manager |
| Release readiness and cutover execution | Release Manager | Project Manager, Developers |
| Cross-team blocker escalation | Technical Program Manager | Product Manager, Project Manager |

## Planning Gate Checklist
- [ ] Primary accountable role assigned for each delivery area above
- [ ] Cross-team dependencies listed with owners and target dates
- [ ] Decision deadlines defined for major technical and scope choices
- [ ] Capacity and staffing assumptions validated by Engineering Manager
- [ ] Test strategy drafted (unit, integration, smoke, manual acceptance)
- [ ] Initial release window and rollback owner identified

## Weekly Execution Checkpoints
- [ ] Dependency status reviewed and high-risk items escalated
- [ ] Blockers mapped to owner with due date and escalation level
- [ ] Scope changes reviewed for timeline and quality impact
- [ ] Defect trend reviewed with remediation owner assigned
- [ ] Stakeholder status update includes decisions needed and risks

## Pre-release Accountability Checks
- [ ] QA Lead confirms quality gate status with evidence
- [ ] Release Manager confirms cutover runbook and rollback steps
- [ ] Project Manager confirms readiness against milestone criteria
- [ ] Product Manager confirms release scope and stakeholder messaging
- [ ] Technical Program Manager confirms cross-team dependencies closed

## Post-release Follow-up
- [ ] Production verification completed and documented
- [ ] Incidents, if any, linked to owners and action items
- [ ] What changed in process captured for retrospective
- [ ] Checklist archived with project artifacts for auditability
