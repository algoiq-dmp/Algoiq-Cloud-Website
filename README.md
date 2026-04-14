# Algoiq Cloud Website

Premium static website for Algoiq Cloud, featuring AI employee solutions and business intelligence dashboards.

## Architecture
- **Structure**: Static HTML/CSS/JS
- **Hosting**: Cloudflare Pages
- **Source**: `public/` directory contains all production-ready files.

## Local Development
To run the website locally:
```bash
npm start
```
The site will be available at `http://localhost:3000`.

## Deployment
This website is automatically deployed to Cloudflare Pages on every push to the `main` branch.
- **Build Command**: `npm run build`
- **Output Directory**: `public`
