# Launchpad — Responsive Internship Board

A framework-free, accessible internship board using semantic HTML, CSS, and vanilla JavaScript.

## Run locally
Open `index.html` in a modern browser. No install or build step is required.

## Data
The board uses the five internship records supplied for this project. Each card displays the internship ID, title, domain, work mode, location, skills, and openings. No company names, stipends, durations, or application URLs were supplied, so the interface does not invent them. “Role details” announces the record details through the status area.

## Features
- Responsive layout for mobile, tablet, and desktop
- Search by ID, role, domain, mode, location, openings, and skills
- Domain filter and reset
- Reusable data array and card renderer
- Empty and defensive error states
- Semantic landmarks, explicit labels, skip link, visible keyboard focus, live announcements, and reduced-motion support
- No framework or third-party dependencies

## Responsive test checklist
Check browser responsive mode at:
- **360px:** filter controls stack and cards display in one column
- **768px:** tablet layout remains readable and controls remain usable
- **Desktop (1280px+):** two-column cards and tips sidebar appear

These are test instructions, not claims of completed visual browser testing. Also test keyboard-only navigation and a search with no matches.

## Publish one view-only link with GitHub Pages
1. Upload `index.html` and `README.md` to the root of a GitHub repository.
2. Go to **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/(root)`, and save.
4. Share the GitHub Pages URL once deployment finishes.
