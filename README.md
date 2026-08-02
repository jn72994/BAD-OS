# BAD-OS  

BAD OS is the internal operating system for B.A.D. Ventures.

Its purpose is to centralize company information, standardize operational workflows, preserve institutional knowledge, and provide a consistent platform for managing the businesses, assets, and activities of the organization.

The system is designed for internal use and will evolve alongside the company.

## Repository Structure

The following represents the intended folder structure for the BAD OS repository. GitHub displays folders alphabetically, so use this as the canonical reference for project organization.

```text
BAD-OS/
│
├── docs/
│   ├── Architecture/
│   ├── Product/
│   ├── Technical/
│   ├── Database/
│   └── UX/
│
├── prototype/
│   ├── index.html
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── app.js
│   ├── pages/
│   │   ├── dashboard.html
│   │   ├── governance.html
│   │   ├── entities.html
│   │   ├── records.html
│   │   ├── compliance.html
│   │   ├── capital.html
│   │   ├── knowledge.html
│   │   └── administration.html
│   └── assets/
│
├── frontend/
├── backend/
├── database/
├── assets/
└── .github/
```

## Folder Purpose

| Folder | Purpose |
|---------|----------|
| docs/ | Documentation and system design |
| prototype/ | Interactive UI prototype (v0.x) |
| frontend/ | Production frontend application |
| backend/ | API and business logic |
| database/ | Database schema and migrations |
| assets/ | Shared images, logos, icons, fonts |
| .github/ | GitHub workflows and templates |

## Development Roadmap

- Phase 0 – Architecture & Documentation ✅
- Phase 1 – Interactive Prototype
- Phase 2 – Core Framework
- Phase 3 – Business Modules
- Phase 4 – Authentication & Security
- Phase 5 – Production Release
