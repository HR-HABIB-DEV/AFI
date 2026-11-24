# HR HABIB Downloader — Vercel package

Made by SK HABIBULLA · Developer HR HABIB.

Redesigned UI with the **ui-ux-pro-max** skill: dark vibrant theme, accessible form labels, loading feedback, and a **Download Now** button that starts the file download.

## Deploy

1. Upload the contents of this folder to a GitHub repository (keep `index.html`, `api/`, `vercel.json` at the repository root).
2. Import the repository in Vercel (Framework Preset: **Other**).
3. In **Project → Settings → Environment Variables** add:
   - `COBALT_API_URL` — base URL of a Cobalt instance you operate or are authorized to use
   - `COBALT_API_KEY` — API key for that instance (if authentication is enabled)
4. Redeploy after saving variables.

This package does not include an API server, a universal free key, or a public provider endpoint. Obtain and configure an authorized Cobalt instance. Never put API keys in `index.html` or commit them to GitHub.

Supported domains are checked server-side. Platform access, formats, login restrictions, and provider limits can prevent downloads. Only download media you own or are authorized to save.
