# My Keeper

Quiet companion PWA.

Live Netlify: https://my-keeper-home.netlify.app/

## Why there is no hero image on the live site

The live Netlify deploy is the **old one-file app**. It never received `hero.jpg`.
`https://my-keeper-home.netlify.app/hero.jpg` is a 404.

If `index.html` is dropped **without** `hero.jpg` beside it, the silk banner stays blank.

## Fix (one file, cannot miss the picture)

Use the single `index.html` that has the silk image **embedded inside it** (data URI).
Drop **only that file** on Netlify → Deploys → Deploy manually.

Headings use metallic gold `#f6e7a1 → #e0b84a → #f3d67a`.
