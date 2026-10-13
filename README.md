# Botanica — Aloe Vera & Cucumber Face Gel

A cinematic, interactive skincare product landing page featuring high-definition scroll-driven 3D canvas animation, smooth frame interpolation, a transparent responsive navigation bar, and clean editorial botanical design.

## Features

- 🌿 **Scroll-Driven Canvas Animation**: Ultra-smooth sequential image canvas rendering (frames 1–170) with lerp smoothing.
- 💧 **Dynamic Overlay**: Text overlay gracefully fades out within the first 30% of scroll progress.
- 🧭 **Transparent Navigation Bar**: Fixed at the top with transparent styling that adapts to a frosted glass background on scroll. Includes direct smooth-scroll menu anchors to:
  - Overview
  - Benefits
  - Ingredients
  - Texture
  - Clinical Trials
  - How to Use
  - Reviews
  - FAQ
- 📱 **Fully Responsive**: Mobile drawer navigation menu with smooth transitions.
- ⚡ **Optimized for Vercel**: Includes `vercel.json` with immutable asset caching for lightning-fast edge delivery.

## Local Development

You can run the site locally using any static web server:

```bash
# Using Node.js / npx
npx serve -l 3000 .

# Or using npm script
npm start
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment on Vercel

1. Push this repository to GitHub: `https://github.com/shifasaifullakhan08-hub/face_gel_website.git`
2. Go to [Vercel](https://vercel.com) and click **"Add New Project"**.
3. Import the `face_gel_website` repository.
4. Leave framework preset as **Other** (Static).
5. Click **Deploy**. Vercel will automatically serve the site globally with CDN edge caching configured via `vercel.json`.
