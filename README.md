# Le Poshe School — Portfolio Website

A complete 6-page concept website for Le Poshe Nursery & Primary School, Parkview Estate, Ikoyi. Built as a portfolio piece. Static HTML, CSS, and JavaScript only. Free to host on GitHub Pages.

---

## File Structure

```
leposhe-site/
├── index.html          → Home page
├── about.html          → Our Story
├── programs.html       → Nursery / Primary / After-school
├── admissions.html     → Apply, process, fees enquiry form
├── gallery.html        → Photo mosaic
├── contact.html        → Visit / call / write
├── css/style.css       → Full design system (one stylesheet)
├── js/main.js          → Mobile nav, scroll reveals, form handling
└── images/             → All photographs (you save the 9 uploaded images here)
```

---

## CRITICAL — Image Setup (Do This First)

The HTML files reference images by exact filename. Save your 9 uploaded photos into the `images/` folder using the filenames below. The site will not render correctly until this is done.

| Your Uploaded Image | Save As (inside `images/` folder) | Used On |
|---|---|---|
| Image 6 — Children in uniform, hands joined in unity circle | `hero-unity.jpg` | Home (hero) |
| Image 5 — Children doing arts & crafts at the gate | `intro-arts.jpg` | Home (intro split) |
| Image 7 — Cultural day, traditional Nigerian attire | `character-cultural.jpg` | Home (character section) |
| Image 5 — Children doing arts & crafts | `about-classroom.jpg` | About (origin) |
| Image 3 — Graduation portraits in caps & gowns | `about-leadership.jpg` | About (leadership) |
| Image 5 — Children doing arts & crafts | `program-nursery.jpg` | Programmes (nursery) |
| Image 3 — Graduation portraits | `program-primary.jpg` | Programmes (primary) |
| Image 7 — Cultural day traditional attire | `program-cultural.jpg` | Programmes (cultural) |
| Image 1 — Boy in pirate costume | `admissions-pupil.jpg` | Admissions |
| Image 2 — Graduation dance performance on stage | `gallery-graduation-dance.jpg` | Gallery |
| Image 3 — Graduation portraits | `gallery-graduates.jpg` | Gallery |
| Image 6 — Unity hands circle | `gallery-unity.jpg` | Gallery |
| Image 4 — Taekwondo group photo (yellow wall) | `gallery-taekwondo.jpg` | Gallery |
| Image 1 — Pirate costume | `gallery-pirate.jpg` | Gallery |
| Image 7 — Cultural day | `gallery-cultural.jpg` | Gallery |
| Image 5 — Arts and crafts | `gallery-arts.jpg` | Gallery |
| Image 8 — Football coaching session | `gallery-football.jpg` | Gallery |
| Image 9 — Taekwondo demonstration on field | `gallery-taekwondo-perform.jpg` | Gallery |

You only have 9 unique images for 18 placement spots, so several photos repeat. That is fine and unavoidable for a first build. If you want more variety later, screenshot more from their Instagram/Google Maps and replace the duplicates.

**The fastest way to do this on your computer:** Open this `leposhe-site` folder. Drag all your downloaded images into the `images/` subfolder. Rename each one to match the table above. Done.

---

## Test Locally First

Before publishing, open `index.html` in your browser (just double-click it). Confirm:

- All 6 pages load and navigate correctly via the top menu
- All images appear (if any are missing, the filename is wrong)
- The site is responsive — resize the browser to mobile width and check the menu collapses to a hamburger
- All forms submit (they show a confirmation message — they don't actually send anywhere yet, which is normal)

If anything looks broken, message me and we fix it.

---

## Publish to GitHub Pages

You already have GitHub since `samueluchenna.github.io` exists. Steps:

**Step 1 — Create a new repository**
Go to github.com → New repository → name it `leposhe-concept` → Public → no README needed → Create.

**Step 2 — Upload the files**
On the new repo's page, click "uploading an existing file." Drag the entire contents of the `leposhe-site` folder (not the folder itself — open it and select everything inside: `index.html`, `about.html`, the `css/`, `js/`, `images/` folders, and so on). Commit changes.

**Step 3 — Enable Pages**
Settings tab → Pages (left sidebar) → under "Source" select `Deploy from a branch` → Branch: `main`, Folder: `/ (root)` → Save.

**Step 4 — Wait 60 seconds**
Your site will be live at:

```
https://samueluchenna.github.io/leposhe-concept/
```

GitHub will show the URL on the Pages settings screen once it's deployed.

---

## What You Can Tell Prospects About This Site

This is **concept work** — a redesign proposal for a real school we identified as having no website. Not a paid client engagement. When showcasing it:

- "Concept site / portfolio piece for Le Poshe School, Parkview Ikoyi — designed to demonstrate end-to-end capability from positioning through to design and code."
- Do not claim Le Poshe hired you. Do not represent it as a live commercial project.
- If asked, "would Le Poshe approve of this?" — you have nothing to hide. It is a respectful, flattering portrayal of a real school you admired. You'd happily share it with them.

---

## Notes for Future Improvements

When you have more time, consider:

- Replace the `hello@leposheschool.ng` email with a real working forwarder
- Wire the forms to a real backend (Formspree, Netlify Forms, or a Google Apps Script)
- Add a favicon (a tiny "L" or school crest)
- Replace placeholder Google Maps coordinates with the exact school location (we approximated Parkview Ikoyi)
- Add Open Graph meta tags so the site previews nicely when shared on WhatsApp / LinkedIn

None of these are needed for portfolio purposes. The site as-is is presentable and complete.

---

Built in one evening. Use it well.
