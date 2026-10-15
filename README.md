# Deshraj Singh — Developer Portfolio

Responsive personal portfolio built with React.js, JavaScript, CSS, and Vite.

## Run locally
1. Install Node.js (LTS).
2. Extract this folder and open it in VS Code.
3. In the terminal run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL printed by Vite (usually `http://localhost:5173`).

Create a production build with `npm run build`.

## Customize before publishing
- Check all project repository links in `src/main.jsx`.
- Verify service descriptions and contact details.
- Project preview cards are **CSS-made concept artwork**, not actual application screenshots. Replace with genuine screenshots only when captured from the running apps.
- Contact button copies your email, with a mailto fallback; no backend is required.

## Free deployment using Vercel
1. Create a GitHub repository named `deshraj-portfolio`.
2. Upload these project files to the repository.
3. Sign in to Vercel with GitHub and choose **Add New → Project**.
4. Import the repository. Framework: Vite; build command: `npm run build`; output directory: `dist`.
5. Click Deploy and use the public URL Vercel gives you.

## Alternative: Netlify
Import the GitHub repository into Netlify, set build command to `npm run build` and publish directory to `dist`, then deploy.
