# Codex Test Repository

This repository and its GitHub Pages site were created entirely using Codex. It exists for personal experiments.

We now have a simple [Next.js](https://nextjs.org) application in the `my-app` directory. The app
renders a basic **Hello World** page.

### Local development

```bash
cd my-app
npm install
npm run dev
```

### GitHub Actions

A GitHub Actions workflow installs dependencies, runs linting as the test step and
executes `npm run build`. Because `next.config.ts` sets `output: 'export'`, the build
produces static files in the `out` directory which are published to GitHub Pages when
changes land on the `main` branch.

