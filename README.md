# Darul Huda Sibaq National Arts Fest ’26 - Launching Site

Interactive launch countdown and portal animation for Darul Huda Sibaq National Arts Fest ’26.

## Hosting on Vercel

This repository is fully configured and ready for **Zero-Config deployment** on Vercel.

### Option 1: Deploy via Vercel Dashboard (Recommended)

1. Push your changes to your GitHub repository (`main` branch):
   ```bash
   git add .
   git commit -m "Configure project for Vercel deployment"
   git push origin main
   ```
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import this repository (`sibaq`).
4. Keep the default settings:
   - **Framework Preset**: `Other`
   - **Root Directory**: `./`
   - **Build Command**: *(leave empty)*
   - **Output Directory**: *(leave empty)*
5. Click **Deploy**.

Your site will be live within seconds!

---

### Option 2: Deploy via Vercel CLI

1. Install Vercel CLI (if not already installed):
   ```bash
   npm i -g vercel
   ```
2. Run deployment from the project root:
   ```bash
   vercel
   ```
3. For production deployment:
   ```bash
   vercel --prod
   ```

---

## Local Development / Preview

To preview the site locally, you can use any static server, such as:

```bash
# Using Python
python3 -m http.server 3000

# Or using npx serve
npx serve .
```

Then visit `http://localhost:3000` in your browser.

---

## File Structure

- `index.html`: Main entry point served at `/` on Vercel.
- `sibaq-launching.html`: Dedicated launch page file (preserved for backwards compatibility).
- `vercel.json`: Vercel routing configuration (`cleanUrls`, rewrites, and security headers).
- `.gitignore`: Prevents OS metadata (`.DS_Store`) and Vercel local folders (`.vercel`) from being tracked.
