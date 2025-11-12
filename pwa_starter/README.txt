# PWA Starter for 台球摆球可视化工具

Files included:
- manifest.json
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png
- icons/maskable-512.png

## How to use
1. Put these files next to your existing `index.html` (same folder).
2. Ensure your `index.html` has:
   - `<link rel="manifest" href="manifest.json">`
   - `<link rel="apple-touch-icon" href="icons/icon-192.png">`
   - Service worker registration: `navigator.serviceWorker.register('service-worker.js')`
3. Deploy the folder to any HTTPS host (GitHub Pages / Netlify / Vercel / Cloudflare Pages).
4. Visit on iPhone Safari → Share → Add to Home Screen.
5. If you update files later, bump the `CACHE_NAME` in `service-worker.js` (e.g., v2) so users get fresh assets.