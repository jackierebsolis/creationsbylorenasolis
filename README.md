# Wildstem Florals website

Plain HTML site, no build step. Works on Vercel as-is.

## Put it online (Vercel)
Option A, no code tools:
1. Go to vercel.com, sign in, click "Add New..." > "Project".
2. Choose to deploy by uploading this folder (or use `npx vercel` from inside it).

Option B, GitHub (best for future edits):
1. Create a new GitHub repo and upload everything in this folder.
2. In Vercel: Add New > Project > import the repo. Framework preset: "Other". Leave build settings empty. Deploy.
3. Every time you change a file on GitHub, Vercel updates the site automatically.

## What to edit in index.html
- Phone, email, Instagram: search for `555`, `hello@`, `yourhandle`
- City: search for `[your city]`
- Colors and fonts: the `:root` block at the top of the <style>
- Photos: see photos/PUT-PHOTOS-HERE.txt
