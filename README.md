# Dashboard page protection
Using Expressjs and Astro
Roadmap:
Frontend : Astro , React js, ShadcnUI ( tailwindcss framework)
- use ShadcnUI in react components
- in the static page, use raw tailwindcss.
- After running npm build, separate the dashboard.html file in a folder (like protected/dashboard.html) in server folder.
- But keep the related assets (like css, js file) in public folder
Backend:
- When user enters dashbaord route, redirect him/her to express dashboard handling route (like: api.domain.com/auth/dashboard). If user authenticatd, send the dashboard file using response.sendFile(path.join(directoryname)+dashboard.html)
