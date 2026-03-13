# Ryan Connelly — Personal Site v2

## Files in this folder

| File | Rename to | Purpose |
|------|-----------|---------|
| RC_index.html | index.html | Home / Hero page |
| RC_philosophy.html | philosophy.html | AI Philosophy & Frameworks |
| RC_resume.html | resume.html | Experience Timeline |
| RC_contact.html | contact.html | Let's Work Together |
| RC_style.css | style.css | Shared styles (all pages link to this) |

## Step 1 — Rename files
Strip the RC_ prefix from all filenames before uploading.
Internal links are already written to the final names.

## Step 2 — Add your resume PDF
Drop your PDF into the same folder and name it:
  ryan_connelly_resume.pdf
The download button on the Experience page already points to this filename.

## Step 3 — Add headshots
Create an `images/` folder and add:
  images/headshot-original.jpg
  images/headshot-enhanced.jpg

Then in index.html, replace the two `<div class="photo-placeholder">` blocks with:
  <img src="images/headshot-original.jpg" alt="Ryan Connelly">
  <img src="images/headshot-enhanced.jpg" alt="Ryan Connelly">

## Step 4 — Activate the contact form (Formspree)
1. Go to formspree.io and create a free account
2. Create a new form — you will get a form ID like `xpwzabcd`
3. In contact.html, find this line:
   action="https://formspree.io/f/YOUR_FORM_ID"
   Replace YOUR_FORM_ID with your actual ID.
4. Free tier: 50 submissions/month. Submissions arrive in your email inbox.

## Step 5 — Push to GitHub Pages
1. Create a GitHub repo named: yourusername.github.io
2. Upload all files (after renaming)
3. Go to Settings > Pages > Source: main branch > Save
4. Site goes live at: https://yourusername.github.io

## Future pages
When ready to add a GitHub repos page or Projects page, create a new HTML file
using the same nav structure and add a link to the nav in all five files.
