SAKURA XD / VERCEL STATIC FRONTEND

Deploy:
1. Extract this ZIP.
2. If the current Sakura backend is NOT https://sakura-xd-frontend-53a8f812f941.herokuapp.com, edit vercel.json and replace that hostname in both /code rewrites with your actual backend Heroku app hostname.
3. Upload/import this folder to GitHub and import it into Vercel. Framework Preset: Other; Build Command: leave empty; Output Directory: . (root).
4. Deploy.

Pages:
 /         main page
 /pair     pairing code page
 /react    reaction page
 /settings settings page
 /admin    admin page

IMPORTANT:
- Pairing codes only work if the backend Heroku app is running and its /code route is healthy.
- The backend needs its required environment variables and MongoDB configuration. Do not put MongoDB URIs or API secrets in this frontend.
- The source has some API features that may rely on backend endpoints. Check browser console/network if a page reports errors.
- Confirm the backend URL before deploying; the hostname in vercel.json is the repository's existing default SITE_URL and may not be the active pairing backend.
