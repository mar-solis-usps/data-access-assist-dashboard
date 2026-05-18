# Data Access Assist Dashboard

A web-based tool that helps USPS employees discover database tables and get step-by-step instructions for requesting the access they need.

## What it does

Users search by their email and table name across one or more catalogs. The results show which tables match and what level of access they currently have. Clicking a table opens a details panel with instructions for requesting read or write access through ARIS and the Databricks Platform.

## Features

- Search by User ID (email) and table name
- Filter results by catalog (SAL, CAT1, CAT2)
- Access status indicators: Full, Partial, or No access
- Detailed per-table instructions for read and write access requests
- Role-based guidance (Analyst, Engineer, Scientist)
- Links to ARIS and Databricks Platform #415

## Tech stack

- HTML5 + Vanilla JavaScript
- [Tailwind CSS](https://tailwindcss.com) (via CDN)
- No build step or dependencies — open `index.html` directly in a browser

## Getting started

```bash
# Clone the repo
git clone <repo-url>
cd data-access-assist-dashboard

# Open in browser
open index.html
```

Or launch with the VS Code debugger (configured for Microsoft Edge via `.vscode/launch.json`).

## Project structure

```
data-access-assist-dashboard/
├── index.html        # Single-page application (all markup, styles, logic)
└── .vscode/
    └── launch.json   # Debug config for Edge
```

## Notes

- This is a frontend-only prototype. Data is currently hard-coded for demo purposes.
- Intended for internal USPS use within the UX Design / WIKI initiative.
