# 3-2-1 Putting Calculator

A small installable Progressive Web App (PWA) built around your putting model.

## Install it on iPhone
1. Publish the contents of this folder to a static HTTPS host (GitHub Pages is a free option).
2. Open the published website in Safari on your iPhone.
3. Tap Share, then **Add to Home Screen**.
4. Name it **3-2-1 Putt**, then tap Add. It will appear as an app icon and can work offline after its first load.

## Publish with GitHub Pages (free)
1. Sign in to GitHub and create a new public repository, for example `putting-calculator`.
2. Upload all five files in this folder (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`) to the repository root.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Open the URL it gives you in Safari on your iPhone and follow the install steps above.

## Formula used
- Base backswing inches = distance in feet up to 20; beyond 20, add 0.5 inch per additional foot.
- Adjusted backswing = base − (Stimp − 9).
- Follow-through = adjusted backswing ÷ 2.
- Break inches = (distance in feet × 2/3 − 1) × slope multiplier (1, 2, or 3).

The app calculates break as a positive number of inches on the high side. The formula is your personal model, not a universal green-reading law.
