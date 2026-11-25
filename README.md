# Portfolio platform — GitHub Pages edition

Static React + Vite demo. No backend required. Existing UI retained. Data starts empty; previous server database and environment credentials are deliberately excluded.

## Run locally
Use Node.js 22: `npm ci`, `npm run dev`. Run `npm test` for local API tests and `npm run build` for the production build.

## GitHub Pages
Extract the ZIP, including the hidden `.github` folder, into the repository root. Commit and push to `main`. In GitHub repository Settings → Pages → Build and deployment, choose GitHub Actions. Run the Deploy to GitHub Pages workflow from Actions if needed. The workflow installs dependencies, tests, builds and deploys `dist`.

## Demo credentials
Admin username `admin`, password `DemoAdmin123!`. Create student accounts using registration. These are public demo credentials, not real security. Do not use real passwords or sensitive data.

## Limitations
Local Storage is browser- and origin-specific. Accounts, portfolios, admin actions and published portfolio views are not shared across browsers or devices. Contact submissions are saved locally and never sent. GitHub integration displays the unconfigured placeholder. Clearing browser data deletes records. Hash routes support refreshes on GitHub Pages. A real shared platform needs a backend and secure authentication.
"# web-development-project" 
