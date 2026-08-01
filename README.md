# This folder IS the website — just upload it to GitHub

Everything in this folder is a finished, working website. Nothing to build.

## How to put it online (2 minutes, no code)

1. On GitHub, create a **new empty repository** (public or private).
2. On the repo page, click **Add file → Upload files** (or drag and drop).
3. **Drag the CONTENTS of this folder** into the upload box.
   - Do this from inside the folder (select all files, including the hidden
     `.nojekyll`), so the files land in the repo **root**, not in a subfolder.
   - If your file manager hides `.nojekyll`, that's fine, it still works.
4. Commit the upload.
5. Go to **Settings → Pages** → under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** → **/(root)** → **Save**
6. Wait a minute. Your site is at:
   `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

That's it. Everything (photos, music, letters) is inside and already works.

## Want a different name for the website address?

Just name your GitHub repository whatever you like, and the site will appear at
`https://YOUR-USERNAME.github.io/THE-REPO-NAME/`. The site adapts to any name
automatically.

## Note

This is a public URL. The lock screen is part of the experience, but everything
in this folder (photos, music, letters) is visible to anyone with the link, so
only share it with people you want to see it.

## Editing the words later

The real source lives in the `src/` folder of the project (see the main
README.md). After changing words there, rebuild with `npm run build` and copy
the new `dist/` over this folder, then re-upload.
