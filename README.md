
Vercel quick deploy:
1) Push this folder to a new GitHub repo.
2) Vercel → New Project → Import Repo → Framework: **Other**; Build Command: **None**; Output Directory: **/** (or leave empty).
3) `vercel.json` ensures the app serves `index.html` and keeps `/api/*` intact.
