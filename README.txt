BG Speaking Calibration — Vercel deployment
Contents: index.html = IELTS Academic Mock Tests V24.1 (Privacy Update), unchanged.
vercel.json = response headers only (microphone allowed for this site, page hidden from search engines,
always serve the latest index.html). No build step, no server code, no database.
Recordings never leave the student's computer: they are created and downloaded in the browser.
Deploy: Vercel → Add New → Project → import this folder from GitHub (Framework preset: Other,
no build command, output directory: root). Or with the Vercel CLI: run "vercel --prod" in this folder.
