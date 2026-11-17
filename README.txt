HAIRBEAUTY - HOW TO RUN / DEPLOY

IMPORTANT: index.html, vercel.json and the "assets" folder must sit together
at the ROOT of your GitHub repo (not inside another folder).

  repo-root/
    index.html
    vercel.json
    assets/   (all images + hero.mp4 + hero-poster.jpg)

Run locally : double-click index.html (or run:  npx serve .)
Deploy      : push these files to GitHub -> Vercel redeploys automatically.
Replace video: put your own video at assets/hero.mp4 (keep under ~8MB, no audio needed).
Social links: edit the three href="#" in the footer with your real page URLs.
