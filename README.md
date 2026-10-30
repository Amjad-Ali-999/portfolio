# Amjad Ali — portfolio

One static page. No build step, no framework. Deploys to Vercel as-is.

## Before you deploy (5 minutes)

1. **Your photo:** add a square or portrait photo named `photo.jpg` to this folder.
   It appears in the About section and the top-left logo. Without it, "AA" initials show instead.
2. **App screenshots:** the `screens` folder has the real screenshots and icons from each app's Google Play listing.
   To change one, replace the file and keep the same name.
3. **Resume:** `resume.pdf` is your latest resume. Replace it when you update it.

## Deploy to Vercel

1. Create a GitHub repo called `portfolio` and upload everything in this folder (including `screens`).
2. On vercel.com: Add New → Project → pick the repo → Framework "Other" → Deploy.
3. Settings → Domains → rename to something like `amjadali.vercel.app`.

## Editing

Everything is in `index.html`. Projects are the `<article class="project">` blocks.
Colours are the `:root` variables at the top of the `<style>` block.
