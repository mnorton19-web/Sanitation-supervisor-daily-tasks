# Sanitation Supervisor Daily Shift Report

Standalone web form for sanitation supervisor end-of-shift reporting.

## What It Includes

- 12-section daily shift report form
- Settings page for supervisors, areas, shifts, support departments, issue types, and default MSS tasks
- Conditional follow-up questions
- Save draft, reset, back/next navigation, and submit flow
- Copy Previous Shift shortcut
- Automatic Shift Readiness score: Ready, Ready With Watchouts, or Not Ready
- Structured area status tracking
- Deep cleaning tracking with type, area, description, and verification
- Cleaning time tracking with area, cleaning type, start/end time, employee count, labor hours, status, and notes
- Repeatable work orders with priority/status
- Photo upload labels and notes
- Local response storage in the browser
- Submission handoff summary with escalation flags
- Admin dashboard with KPI tiles, filters, trend cards, response detail view, and CSV export
- Mobile-friendly layout for shop-floor use

## GitHub Pages

This repository is ready for GitHub Pages because the main file is `index.html`.

To publish:

1. Create a GitHub repository.
2. Upload `index.html` and `README.md`.
3. In the repository, open **Settings > Pages**.
4. Set source to **Deploy from a branch**.
5. Select the `main` branch and `/root`.
6. Save.

GitHub will provide a public website URL after deployment.

## Storage Note

Responses are stored in the browser on the device where the form is used. For shared multi-user storage, connect a backend such as SharePoint, Microsoft Lists, Google Sheets, Supabase, or a small server endpoint.
