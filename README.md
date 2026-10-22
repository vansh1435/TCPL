# TCPL Recruitment Website

A self-contained static website for **TCPL तेल चिटाई प्राइवेट लिमिटेड**.

## Files
- `index.html` — website, styling, interactive application form, and confirmation popup.
- `vercel.json` — minimal Vercel configuration for clean URLs.

## Deploy to Vercel

### Option 1: Deploy from the Vercel dashboard
1. Extract this ZIP on your computer.
2. Open https://vercel.com/new and import a Git repository containing these files, or use Vercel CLI as described below.
3. If prompted for a framework, select **Other**.
4. Leave Build Command and Output Directory empty (or use `.` as the output directory if required).
5. Deploy. `index.html` is the site entry point.

### Option 2: Deploy with Vercel CLI
1. Install Node.js, then install the Vercel CLI: `npm i -g vercel`
2. Open a terminal in the extracted project folder.
3. Run `vercel` and follow the prompts.
4. For production deployment, run `vercel --prod`.

## Important application-form note
The form currently validates input and displays a success message in the browser. It does **not** persist or email applications, and the generated application ID is only a demo ID. Before using this for real recruitment, connect a secure backend/database or a form service, add server-side validation, and publish an appropriate privacy notice. Do not collect real applicant data until storage and access controls are configured.
