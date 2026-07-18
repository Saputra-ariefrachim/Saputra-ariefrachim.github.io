# Arief's Portfolio Site

## What's inside
- `index.html` — the whole website (design, content, and interactions in one file)
- `Lebenslauf_Saputra.pdf` — your CV, linked from the "Download my CV" button

## How to preview locally
Just double-click `index.html` — it opens in your browser.

## How to publish (GitHub Pages, free, ~10 min)
1. Create a free account at github.com (if you don't have one)
2. Create a new repository, e.g. `arief-portfolio` (public)
3. Upload BOTH files from this folder (index.html + the PDF)
4. Go to Settings → Pages → Source: "Deploy from a branch" → Branch: main → Save
5. After a minute your site is live at: https://YOURUSERNAME.github.io/arief-portfolio/

Later you can buy a domain (e.g. ariefsaputra.com, ~10 EUR/year) and connect it in the same Pages settings.

## How to edit
Open `index.html` in any text editor (VS Code, Notepad++).
- Colors: all in one place at the top, inside `:root { ... }`
- Sections are labeled with comments like `===== SECTION: PROJECTS =====`
- To add a project card: there is a ready commented-out TEMPLATE at the end of the projects grid — copy, uncomment, edit
- To add a new job: copy one `<div class="stop">...</div>` block in the Journey section
- If you update your CV, replace the PDF but KEEP the same filename (Lebenslauf_Saputra.pdf), or update the link in the hero button

## Add your photo
Drop a photo named exactly `photo.jpg` into this folder (next to index.html).
It will automatically appear in the "A little about me" section.
No photo = the slot hides itself, nothing breaks.
Remember to upload photo.jpg to GitHub together with the other files.
