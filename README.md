# Cloudflare Pages Setup

This repository uses Cloudflare Pages **native GitHub integration** - no manual configuration required!

## 🚀 Zero-Config Setup

### Automatic Deployment
- **Production**: Every push to `main` → https://speakmcp.pages.dev
- **Preview**: Every pull request → Unique preview URLs
- **No GitHub Actions or secrets needed**

### Setup Steps
1. Go to [Cloudflare Pages](https://dash.cloudflare.com/pages)
2. Create new project → Connect to Git → Select this repository
3. Configure:
   - Build command: *(leave empty for static site)*
   - Build output directory: `/`
   - Production branch: `main`
4. Deploy automatically on every push

### Features
- ✅ SSL certificates (automatic)
- ✅ Global CDN distribution
- ✅ Atomic deployments (zero downtime)
- ✅ Preview deployments for PRs
- ✅ Custom domain support (optional)
