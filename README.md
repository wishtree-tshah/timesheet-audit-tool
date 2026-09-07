# Timesheet Audit Tool

A browser-based Excel/CSV timesheet auditor with project summaries and client email drafts.

## Project directory and email details

Use **Manage project directory** to add or update:

- Project ID, display name, and Excel aliases
- Client POC and the email greeting name
- To and CC email addresses
- Project resources and the roles shown in email summary tables

When an uploaded timesheet contains a new project, an unknown resource, or a project without recipient details, the tool opens the directory form with the project and resource names pre-filled. Saved changes are applied to the current report and future uploads.

Directory updates are stored only in that browser's `localStorage`. They are not uploaded or written back to the repository, so a different browser or device maintains a separate directory.

## Run

Open `index.html` in a modern browser, then upload an `.xls`, `.xlsx`, or `.csv` timesheet.
