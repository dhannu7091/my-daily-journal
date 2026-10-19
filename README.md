# My Daily Journal

A responsive, no-build daily journal app inspired by the supplied journal form.

## Features
- Daily entry form with mood selection and six reflection prompts
- Copy an entry in a clean, consistent text format
- Save and update entries in browser localStorage
- Browse, search, filter by month, edit, and delete past entries
- Entry count and consecutive-day streak
- Export/import JSON backups
- Responsive layout for mobile and desktop

## Run locally
Open `index.html` in a modern browser. No install or build step is required.

## Deploy to GitHub Pages
1. Create a new GitHub repository (for example, `my-daily-journal`).
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for the Pages deployment and open the URL GitHub provides.

## Important storage note
GitHub Pages is static hosting, not a database. This version stores entries in the current browser using `localStorage`; entries do not automatically sync between devices or browsers. Export backups regularly. If browser data is cleared, local entries can be lost. For account-based cloud sync, connect a hosted database such as Supabase or Firebase and add authentication plus database access rules. Do not store private journal entries in a public GitHub repository.
