# Deploy Landing Page to Vercel (FREE — 2 minutes)

## Option 1: Drag & Drop (Easiest — No GitHub needed)

1. Go to **https://vercel.com/new**
2. You'll see a box that says **"Drag and drop your project"**
3. Open your computer's file explorer
4. Go to: `D:\jamessten560\The Initiators pro\landing-page\`
5. **Drag the entire `landing-page` folder** onto the Vercel drop box
6. Wait 30 seconds — your page is LIVE! 🎉

## Option 2: Deploy from GitHub (Recommended)

1. Push your code to GitHub (you already did this)
2. Go to **https://vercel.com/new**
3. Click **"Import Git Repository"**
4. Select your `The-Initiators-pro` repo
5. In **"Root Directory"**, click "Edit" → select **`landing-page`**
6. Framework Preset: **Other**
7. Click **Deploy**
8. Done! ✅

## After Deployment

1. Vercel gives you a URL like: `https://your-project.vercel.app`
2. You can set a custom domain in Vercel settings (e.g., `theinitiators.app`)

## Before Publishing — Update These Links

Open `index.html` and replace these two placeholders:

1. **APK Download Link**: Search for `APK_URL_PLACEHOLDER`
   - Replace with your actual APK download URL (GitHub release link or direct URL)

2. **Play Store Link**: Search for `PLAYSTORE_URL_PLACEHOLDER`
   - Replace with your Google Play Store link once published

### Example:
```
BEFORE: href="APK_URL_PLACEHOLDER"
AFTER:  href="https://github.com/jamal1608/The-Initiators-pro/releases/download/v1.0.1/app-release.apk"
```