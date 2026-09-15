# LocalAI — GitHub + Vercel

## Deploy
1. Create a GitHub repository named `localai`.
2. Upload all files from this folder to the repository.
3. In Vercel choose Add New Project and import the GitHub repository.
4. For this static version, no build command is required. Vercel will serve `index.html`.
5. After deployment, copy the Vercel URL.
6. In Supabase go to Authentication → URL Configuration and set the Site URL to the Vercel URL.
7. Test registration/login from the Vercel URL, not from the Files app.

## Security
`config.js` contains only the Supabase Project URL and Publishable Key. Never put a Supabase Secret Key or service_role key in this repository or frontend.
