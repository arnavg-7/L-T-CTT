# L&T CTT — Skilling LMS (Learner Portal)

Interactive front-end mockup of the **student / learner side** of the L&T CTT Skilling
LMS, designed in the **L&T PCT** visual language.

- `index.html` — self-contained single-file mockup (no build step, no dependencies).
  Open it directly in a browser, or deploy the repo to any static host.

## Screens
Dashboard (detailed course cards, timetable, pending assessments, grades, mentoring),
My Courses, Course Content, Assessments (MCQ), My Grades, My Attendance, Timetable,
Mentoring, Discussion Forum, Events, My Profile. Light + dark theme, fully responsive.

## Deploy (staging)
Any static host works since it's a single file:
- **Netlify:** connect this repo (no build command, publish directory = repo root), or drag the folder to app.netlify.com/drop.
- **GitHub Pages:** Settings → Pages → deploy from `main` / root.
- **Vercel / Cloudflare Pages:** import repo, framework preset = "Other", output = root.
