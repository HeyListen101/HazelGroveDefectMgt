# 🐞 HazelGrove Defect Management Repository

Welcome to the **Defect Management Repo for Project HazelGrove**. This repository is dedicated to identifying, documenting, tracking, and resolving defects throughout the development lifecycle of HazelGrove.

---

## 🚧 Purpose

This repository is used to:

- Report and categorize software defects in HazelGrove.
- Track defect lifecycle from discovery to resolution.
- Maintain transparency and history of known issues and their fixes.
- Facilitate communication between QA, developers, and stakeholders.

---

## 📁 Repository Structure

hazelgrove-testing/
├── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       ├── feature_request.md
│       └── test_case.md
├── defects/
│   └── [defect-id]/
│       ├── description.md
│       ├── logs.txt
│       └── screenshots/
├── README.md
└── CONTRIBUTING.md

---

## 🐛 Reporting a Bug

1. Use the `description.md` template under `ISSUE_TEMPLATE/` to file a bug.
2. Create a new folder under `defects/` using the format: `BUG-XXXX`.
3. Fill in `description.md` with the appropriate information
4. Add logs to `logs.txt` and place any screenshots in the `screenshots/` folder.

---

## 🔍 Labels

| Label            | Description                            |
|------------------|----------------------------------------|
| `bug`            | Verified defect                        |
| `unconfirmed`    | Needs validation                       |
| `high-priority`  | Blocking or critical                   |
| `medium`         | Important but not blocking             |
| `low`            | Cosmetic or minor                      |
| `UI`             | User interface issue                   |
| `backend`        | Backend/service issue                  |
| `performance`    | Speed or resource usage issue          |
| `security`       | Security vulnerability or flaw         |

---

## ✅ Workflow

1. Bug is reported via issue template.
2. Issue is triaged and labeled appropriately.
3. Folder is created under `/defects/` to house evidence and description.
4. Developers reference `BUG-XXXX` in commits and pull requests.
5. QA verifies the fix before marking as closed.