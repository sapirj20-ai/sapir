# sapir — Portfolio

This repository contains my portfolio site.

How to publish (quick method)
1. Ensure GitHub Pages is set to Branch: `main`, Folder: `/docs`.
2. The site is served from `docs/index.html` — this file is already included.
3. Commit and push, then wait ~1 minute. Visit:
   `https://sapirj20-ai.github.io/sapir/`

Commands to add the provided files and publish:
```bash
 git checkout main
 mkdir -p docs
 # (place docs/index.html file in the docs/ directory)
 git add docs/index.html README.md
 git commit -m "Add portfolio homepage"
 git push origin main
```

If you use a framework (Next/Gatsby/Hugo), let me know and I will give a recommended GitHub Actions workflow instead.