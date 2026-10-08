# Reflection: brian-team_brian2genn

**NetID:** kbc177
**Project:** brian-team/brian2genn
**Analysis date:** 2025-09-30

## 1. Overview
- Total commits: ~970
- Authors: 15+
- GitHub stars / forks: 51 / 17
- Last commit: ~6 months ago

## 2. Inactivity Patterns
The project has multiple short gaps (2–3 months) throughout its history,
but one dominant gap of **13 months (2023-08 → 2024-08)** stands out. This
is the longest real dormancy in the dataset after AeroPython and AFQ-Browser.

## 3. Longest Gap Analysis
- **Longest gap:** 2023-08 → 2024-08 (13 months)
- **Commits before gap (top themes):** Other:Feature development
- **Commits after gap (top themes):** Automated bot contributions:Other
- **Commits after the gap:** many (project is active again)
- **Was the gap easy or hard to interpret?** Easy to spot, harder to
  explain. The 13-month silence coincides with major upstream changes in
  both Brian2 (v2.5 → v2.7) and GeNN (v4.x → v5.x).

## 4. Hypothesized Reason for Inactivity
brian2genn is a **thin bridge** between two fast-moving upstream projects
(Brian2 and GeNN). Any breaking change in either dependency halts
compatibility work. The 2023 gap likely reflects maintainers waiting for
upstream APIs to stabilize before porting the integration layer. This is a
classic "dependency-driven pause".

## 5. Recovery
- **Did it recover?** Yes
- **Why did it recover?** The post-gap commits are dominated by
  **Automated bot contributions** (Dependabot updates) — meaning the
  project's GitHub Actions were still active and eventually pulled the
  pinned dependencies forward.
- **Who drove the recovery?** Dependabot (bot) followed by maintainer
  review by Marcel Stimberg.

## 6. Current Status
- **Current status:** **Inactive** (last commit ~6 months ago, before
  2025-04-01)
- **Recent themes (last 10 commits):** Automated bot contributions:Other

## 7. Summary
brian2genn's 13-month dormancy reflects its role as a version-compatibility
shim between Brian2 and GeNN. Recovery was driven primarily by automated
Dependabot updates rather than human-initiated development. As of
2025-09-30 the project appears Inactive, with only bot activity in the
last 6 months.