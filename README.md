# alf-backup

Automated backup is configured via GitHub Actions:

- Workflow: `.github/workflows/backup-google-doc.yml`
- Schedule: every 10 minutes
- Source: Google Doc `1-AtKUh-xE1CPRRDVlfPx1d42Trhr7F8qQIw69hP85Ds`
- Output: `backups/google-doc.md` (combined backup of Main and Red Flags tabs)
- Access: document must be publicly readable
