# Deployment Plan: Karobix Landing Page

This plan outlines how to publish your landing page along with the APK files to GitHub Pages, Netlify, or Vercel.

## 1. Prepare the Files
The following files are now ready in `karobix-web/`:
- `index.html`: The main landing page with updated download links.
- `app-arm64-v8a-release.apk`: The modern Android version (ARM64).
- `app-armeabi-v7a-release.apk`: The version for older devices (v7a).

## 2. Option A: GitHub (Recommended)
1. **Create a new Repository** on GitHub (e.g., `karobix-landing`).
2. **Upload the contents** of the `karobix-web` folder (drag and drop `index.html` and the two `.apk` files).
3. **Go to Settings > Pages** in your GitHub repo.
4. Under **Build and deployment**, select `Deploy from a branch` and choose `main` and the `/ (root)` folder.
5. Click **Save**. Your site will be live at `https://<your-username>.github.io/karobix-landing/`.

## 3. Option B: Netlify (Fastest)
1. Go to [Netlify](https://www.netlify.com/).
2. Drag and drop the entire `karobix-web` folder onto the deployment area.
3. It's live instantly!

## 4. Option C: Vercel
1. Run `npx vercel` in the `karobix-web` folder.
2. Follow the prompts.
