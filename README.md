# Amjad Ali — portfolio

A single static page. No build step, no framework.

## Deploy to Vercel

**Option 1: drag and drop (fastest)**
1. Unzip this folder.
2. Go to vercel.com/new, sign in, and pick "Deploy" → upload the folder (or run `npx vercel` inside it).
3. Vercel gives you a link like `amjad-ali.vercel.app`.

**Option 2: GitHub (best for updates)**
1. Create a new GitHub repo and push these files.
2. On vercel.com/new, import the repo. Framework preset: "Other". Leave build command empty.
3. Every push updates the live site.

After deploying, put the link in your LinkedIn contact info (Website → "Portfolio") and in your Featured section.

## Editing

Everything is in `index.html`:
- Projects: the `<ul class="work">` list. Add app names and App Store / Play Store links once you can share them.
- Contact details: the `.contact` section near the bottom.
- Colours: the `:root` variables at the top of the `<style>` block.
