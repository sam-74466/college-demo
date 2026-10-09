# College Management System — Demo Website

A static frontend prototype for demonstrating the college management requirements.

## Features
- Separate Student, Teacher, and Admin demo portals
- Fictional sample student data only
- Excel/Calc (`.xlsx`) and CSV import preview
- Course-wise and teacher-wise student filtering
- Student Satisfaction Survey and seven placeholder feedback forms
- Feedback completion percentages and red/green status indicators
- Internal/external examination setup and seat-number preview
- Roll-number-wise room seating layout

## Run locally
Download the files and open `index.html` in a modern browser. No npm installation or build step is required.

## Publish using GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `college-logo.png`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/(root)`, then save.
6. Wait for GitHub Pages to publish the site; the URL will appear in the Pages settings.

## Important limitations
This is a demo frontend, not a production system. The portal buttons only simulate role access; they are not secure authentication. Demo changes are stored in the current browser and are not shared between users. Spreadsheet reading uses SheetJS from a CDN and therefore requires internet access. Do not upload real student data or use this demo for confidential college records. A production version requires a backend, database, real authentication, server-side authorization, and backups.
