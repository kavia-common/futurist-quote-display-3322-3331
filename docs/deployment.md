# Deployment Notes

## Production Deployment

The Jarvis-Inspired Quote Display App is a standard React single-page application (SPA) suitable for deployment on any static web host or cloud platform (e.g., Vercel, Netlify, AWS Amplify, GitHub Pages, or a self-managed VPS/Nginx environment).

### Build the App

```bash
cd futurist-quote-display-3322-3331/jarvis_quote_frontend
npm install
npm run build
```

- This creates an optimized build in the `build/` folder.

### Deploying the Build

- Upload the contents of the `build/` folder to your static host.
- Configure environment variables as required for your hosting environment.
- The app expects to be served from the root path. For subdirectory hosting, adjust `homepage` in `package.json` and, if needed, any `PUBLIC_URL` environment variables.

### Runtime Configuration

- The app reads static variables at build time; changes to most environment variable values require a rebuild.
- Ensure the `REACT_APP_PORT` is set to `3000` unless your host specifies another port, especially when running standalone.
- The preview system uses port 3000 by default.

### Precautions

- Do **not** attempt to start the app process manually if a managed preview system (e.g., CI/CD, cloud preview, or container preview) is already active.
- Do not commit `.env` files or credentials to your repository.

---

**Summary:** Standard React SPA deployment process applies. For custom domains or server-side integrations, ensure API endpoints and environment configuration are correctly set.

Task completed: Deployment notes documented.
