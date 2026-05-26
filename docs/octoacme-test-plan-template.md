# OctoAcme — Test Plan Template

Use this template at the start of each sprint or release to define the QA approach. The QA Engineer owns this document and coordinates with Developers, PdM, and PM.

---

## 1. Overview

| Field | Details |
|---|---|
| Project / Feature | |
| Sprint / Release | |
| QA Engineer | |
| Date | |

---

## 2. Scope

### In Scope
List the features, user stories, or acceptance criteria that will be tested in this cycle.

- 
- 

### Out of Scope
List any areas explicitly excluded from this test cycle and the reason.

- 

---

## 3. Test Approach

Describe the testing strategy for this cycle. Include the mix of:
- **Unit tests**: owned by Developers; run in CI on every PR.
- **Integration tests**: owned by Developers/QA Engineer; run in CI.
- **Manual functional tests**: owned by QA Engineer; executed before release candidate.
- **Exploratory tests**: owned by QA Engineer; focused on edge cases and UX flows.
- **Regression tests**: owned by QA Engineer; confirm no existing behavior is broken.
- **Accessibility / usability checks**: coordinated with UX/UI Designer.

---

## 4. Test Cases

| ID | Feature / Story | Test Scenario | Expected Result | Actual Result | Status | Notes |
|---|---|---|---|---|---|---|
| TC-001 | | | | | | |
| TC-002 | | | | | | |

Status values: `Pass` / `Fail` / `Blocked` / `Not Run`

---

## 5. Defect Tracking

All defects should be logged as GitHub Issues with the `bug` label and linked to the relevant user story.

| Defect ID | Description | Severity | Status | Owner |
|---|---|---|---|---|
| | | | | |

Severity: `Critical` / `High` / `Medium` / `Low`

---

## 6. Entry and Exit Criteria

### Entry Criteria (test cycle can begin when)
- [ ] All stories in scope are code-complete and merged to the test branch
- [ ] CI is green (unit and integration tests passing)
- [ ] Test environment is available and seeded with test data
- [ ] Acceptance criteria are documented and agreed upon with PdM

### Exit Criteria (release can proceed when)
- [ ] All test cases have been executed
- [ ] No open Critical or High severity defects
- [ ] All Medium severity defects have mitigation plans documented
- [ ] QA Engineer has provided formal sign-off
- [ ] Doc review checklist completed (see `octoacme-doc-review-checklist.md`)

---

## 7. Risks and Mitigations

| Risk | Impact | Mitigation |
|---|---|---|
| | | |

---

## 8. Sign-off

| Role | Name | Date | Status |
|---|---|---|---|
| QA Engineer | | | |
| Product Manager (PdM) | | | |
| Project Manager (PM) | | | |
