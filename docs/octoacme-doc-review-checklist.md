# OctoAcme — Documentation Review Checklist

Use this checklist before each release to ensure user-facing and internal documentation is accurate, complete, and published. The Technical Writer owns this checklist and coordinates reviews with Developers, PdM, QA Engineer, and Support Engineer.

---

## 1. Release Information

| Field | Details |
|---|---|
| Feature / Release | |
| Technical Writer | |
| Review Date | |
| Target Publish Date | |

---

## 2. Documentation Scope

List all documentation artifacts that need to be created or updated for this release.

| Document | Type | Owner | Status |
|---|---|---|---|
| | User Guide / Help Article | Technical Writer | |
| | API / Developer Docs | Technical Writer + Developer | |
| | Release Notes | Technical Writer | |
| | Internal Runbook | Technical Writer + Developer | |
| | FAQ / Knowledge Base Article | Technical Writer + Support Engineer | |

Status values: `Not Started` / `Draft` / `In Review` / `Published`

---

## 3. Content Review Checklist

### Accuracy
- [ ] All documented feature behaviors have been validated against the implemented code (confirmed with Developer or QA Engineer)
- [ ] Screenshots and UI references reflect the current shipped UI (confirmed with UX/UI Designer)
- [ ] API endpoints, parameters, and examples are correct and tested

### Completeness
- [ ] All new or changed features from this release are documented
- [ ] Edge cases and error states are documented where relevant
- [ ] Prerequisites, limitations, and known issues are noted

### Clarity and Style
- [ ] Language is clear, concise, and uses consistent terminology
- [ ] Content follows the OctoAcme style guide (if applicable)
- [ ] No internal jargon or placeholder text remains

### Accessibility
- [ ] Images include descriptive alt text
- [ ] Tables have clear headers
- [ ] Code samples are formatted in code blocks

---

## 4. Stakeholder Reviews

| Reviewer | Role | Review Focus | Approved | Date |
|---|---|---|---|---|
| | Developer | Technical accuracy | | |
| | QA Engineer | Test coverage reflected, defect notes | | |
| | Product Manager (PdM) | Feature coverage and messaging | | |
| | Support Engineer / Customer Success | Customer-facing clarity, FAQ gaps | | |

---

## 5. Release Notes Checklist

- [ ] Release notes drafted and reviewed by PdM for messaging accuracy
- [ ] All shipped features and bug fixes are listed
- [ ] Breaking changes are clearly flagged
- [ ] Migration steps (if any) are documented
- [ ] Release notes reviewed by Support Engineer to prepare support team
- [ ] Release notes published before or at the time of release

---

## 6. Publication Checklist

- [ ] All documentation updates merged to the main branch or published to the docs platform
- [ ] Internal knowledge base articles updated (coordinated with Support Engineer)
- [ ] Links verified — no broken links in published docs
- [ ] Technical Writer has notified the Support Engineer that docs are live
- [ ] Doc status updated in project board

---

## 7. Sign-off

| Role | Name | Date | Approved |
|---|---|---|---|
| Technical Writer | | | |
| Product Manager (PdM) | | | |
| Support Engineer / Customer Success | | | |
