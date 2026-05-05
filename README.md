# Ibstock ScanDraft QR

Static web app for creating QR-linked records from:

- Upload Image / PDF
- QA Sheet
- Drawing Pad

## Upload to GitHub

1. Create a new GitHub repository.
2. Upload all files from this ZIP into the root of the repository.
3. Commit to the `main` branch.
4. Go to **Settings → Pages**.
5. Choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. GitHub will give you a live website URL.

## Important

This is currently a static front-end app. For company-wide production use, it still needs:

- secure hosting/domain approval
- backend storage
- authentication
- database
- audit logs

## QR URL

Inside `index.html`, search for:

```text
qr.ibstock.example
```

Replace it with your GitHub Pages URL or future company domain.
