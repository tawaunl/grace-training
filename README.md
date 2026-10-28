# Hosting Grace's Training on GitHub Pages (no banner, home screen app)

1. Sign in at github.com and click New repository. Name it `grace-training`. Choose Public. Create it.
2. Click "uploading an existing file". Drag in all five files from this folder: index.html, manifest.webmanifest, icon-180.png, icon-192.png, icon-512.png. Click Commit changes.
3. Go to Settings, then Pages. Under Build and deployment choose "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. Wait about a minute. Your link will be https://YOUR-USERNAME.github.io/grace-training/
5. Open that link on Grace's iPhone in Safari, tap Share, then Add to Home Screen. It opens full screen with its own icon and no Google banner.

If you ever redeploy the Apps Script as a brand new deployment, the /exec link changes. Edit index.html on GitHub (pencil icon) and paste the new link into the two places it appears.
