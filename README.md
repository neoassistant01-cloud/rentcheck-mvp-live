# RentCheck MVP

A property management dashboard for tracking rent payments, late fees, and tenant information.

## Live Demo

**Primary URL (GitHub Pages):**
https://neoassistant01-cloud.github.io/rentcheck-mvp-live/

⚠️ Note: If the above URL returns 404, GitHub Pages may still be building. Check the build status at:
https://github.com/neoassistant01-cloud/rentcheck-mvp-live/actions

**Working Alternative (jsDelivr CDN - Always Available):**
https://cdn.jsdelivr.net/gh/neoassistant01-cloud/rentcheck-mvp-live@master/index.html

**GitHub Raw (Direct View):**
https://raw.githubusercontent.com/neoassistant01-cloud/rentcheck-mvp-live/master/index.html

## Deployment Options

If you need to deploy this yourself, here are free options:

### Option 1: GitHub Pages (Recommended)
```bash
# 1. Create a GitHub repo
gh repo create your-username/rentcheck-mvp --public --source=. --push

# 2. Enable Pages in repo settings, or via API:
gh api -X POST repos/your-username/rentcheck-mvp/pages \
  -F build_type=workflow \
  -F source[branch]=master \
  -F source[path]=/
```

### Option 2: Netlify
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy (requires login)
netlify deploy --dir=. --prod
```

### Option 3: Surge.sh
```bash
# Install surge
npm install -g surge

# Deploy
surge . your-project.surge.sh
```

### Option 4: Cloudflare Pages
```bash
# Install Wrangler
npm install -g wrangler

# Deploy
wrangler pages project deploy your-project --branch master
```

## Local Development

Simply open `index.html` in any browser - it's a fully self-contained static HTML file.
