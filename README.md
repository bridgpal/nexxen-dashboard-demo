# Nexxen Campaign Insights (demo)

A single static HTML dashboard used to demo Netlify's Git-based continuous deployment.

- `index.html` is the whole site. Edit it, commit, push to `main`, and Netlify redeploys automatically.
- `netlify.toml` tells Netlify there is no build step and to publish the repo root.

## Deploy from the CLI (without Git)

```sh
npm i -g netlify-cli        # once
netlify link                # once, pick the existing site
netlify deploy --prod --dir .
```

Drop `--prod` to get a draft deploy on a unique preview URL instead of updating production.
