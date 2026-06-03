How to install on iPhone as a PWA

1) Upload the contents of this folder to a website.
   Easiest free options: GitHub Pages or Netlify.

GitHub Pages method:
1. Go to github.com and sign in.
2. Click + > New repository.
3. Name it: 6week-plan
4. Choose Public.
5. Click Create repository.
6. Click Add file > Upload files.
7. Upload: index.html, manifest.json, service-worker.js, and the icons folder.
8. Click Commit changes.
9. Go to Settings > Pages.
10. Under Branch, choose main and /root, then Save.
11. Wait until GitHub gives you a Pages link.
12. Open that link in Safari on your iPhone.
13. Tap Share > Add to Home Screen > Add.

Netlify method:
1. Go to netlify.com.
2. Drag the whole 6week-pwa folder into Netlify Drop.
3. Open the generated link in Safari on your iPhone.
4. Tap Share > Add to Home Screen > Add.

After opening once online, the app should continue working offline because the service worker caches the files.
