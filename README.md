# Atchatha Portfolio (GitHub Pages)

**Quick start**  
1. Create a public repo named `atchatha.github.io` (exactly).  
2. Upload all files in this ZIP to that repo (drag & drop in GitHub → “Add file” → “Upload files”).  
3. Go to **Settings → Pages** and set **Build from a branch** → **Branch: main** → **Save**.  
4. Visit https://atchatha.github.io

**Edit these right away**
- `_config.yml`: update `author.email`, and your social links.
- `index.md`: tweak the About text.
- (Optional) `google_site_verification` and `google_analytics` in `_config.yml`.

**Add skills to the timeline**
Edit `index.md` and add blocks like:
```
<div class="timeline-item">
  <div><strong>Oct 2025 — SQL</strong></div>
  <div class="meta">Queries, joins, CTEs, performance tuning</div>
</div>
```

**Add projects**
Inside the "Projects" section in `index.md`, duplicate the card snippet and fill your links.

**Blog posts**
Create new files under `_posts/` named `YYYY-MM-DD-your-title.md`.

**Troubleshooting**
- If the site doesn’t appear, check **Actions** tab for “Pages build and deployment” logs.
- Ensure the repo is named exactly `atchatha.github.io`.