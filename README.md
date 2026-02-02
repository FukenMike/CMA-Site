# Chaos Management Agency

Digital infrastructure and operations support for nonprofits and small organizations.

## About

Chaos Management Agency (CMA) provides digital infrastructure and operations support to help small nonprofits and community programs reduce technology costs, simplify tools, and build stable, low maintenance websites.

## Services

- **Website Rebuild and Hosting Migration** — Rebuild simple, fast, secure sites and move off expensive hosts. Deploy on Cloudflare Pages or Netlify with clean domain setup.
- **Technology Cost Reduction and Cleanup** — Audit your current tools and subscriptions, remove what you do not need, and simplify the stack so fewer things break.
- **Digital Infrastructure Setup** — Domains, DNS, email basics, forms, intake routing, and handoff documentation so your foundation is stable.
- **Nonprofit Website Foundations** — Template based nonprofit sites with the pages that build trust: programs, contact, transparency, and policy basics.

## Local Preview

Open `index.html` in a browser, or use a simple local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server
```

Then visit `http://localhost:8000`

## Deploy

This is a static site with no build process.

**Netlify:**
- Connect your GitHub repo and deploy
- Or drag and drop the folder into Netlify's dashboard

**Cloudflare Pages:**
- Connect your GitHub repo
- Build settings: None required (static site)

## Tech Stack

- Static HTML, CSS, and JavaScript
- No build tools or dependencies
- SEO-optimized with JSON-LD schema and social metadata
