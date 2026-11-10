# مرافئ | MARAFE’ — Previews

**Where Stories Find Their Harbor** — حيث تجد الحكايات مرفأها
Powered by SHAHINO AI

Static visual previews (sample data only, no backend):

| Path | What it is |
|---|---|
| `/` (`index.html`) | User app preview: home, marketplace, library, profile, buy sheet with payment methods |
| `/admin/` (`admin/index.html`) | Admin dashboard preview: orders, payment methods, book review, badges, commission calculator |

Both support Arabic/English (RTL/LTR) and light/dark modes.

## Publish on GitHub Pages
1. Create a new repository and upload all files in this folder (keep `.nojekyll`).
2. Repository → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / folder `/ (root)` → Save.
3. After a minute the site is live at `https://<username>.github.io/<repo>/` and the admin preview at `.../admin/`.

## Git from the terminal
```bash
git init
git add .
git commit -m "MARAFE previews"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

> The real app (Flutter + Firebase) and the admin dashboard source are separate from these previews.
