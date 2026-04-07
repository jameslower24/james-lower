# James [LastName] — Personal Website
## IS 201 Final Web Development Project

---

## File Structure

```
site/
├── index.html          ← Home page (Bootstrap)
├── resume.html         ← HTML résumé (Bootstrap)
├── blog.html           ← Blog/Writing page (Bootstrap)
├── ecuador.html        ← Scratch page (no Bootstrap) ✦ RUBRIC PAGE
├── webapp.html         ← Ecuador Quiz web app (linked from ecuador.html)
├── css/
│   ├── custom.css      ← Styles for Bootstrap pages
│   └── ecuador.css     ← Styles for scratch page (no Bootstrap)
├── js/
│   └── main.js         ← Navbar scroll + fade-in animations
└── Images/
    └── Quito.jpeg      ← (Add your own images here)
```

---

## Before You Go Live — Fill These In

Search for `[LastName]`, `[your@email.com]`, and `[your-profile]`
across all files and replace with your real info.

---

## 1. Add Your YouTube Video (ecuador.html)

1. Go to YouTube and find a video about Ecuador you like.
2. Copy the **video ID** from the URL. Example:
   - URL: `https://www.youtube.com/watch?v=abc123xyz`
   - Video ID: `abc123xyz`
3. Open `ecuador.html` and find this line:
   ```
   src="https://www.youtube.com/embed/VIDEO_ID_HERE"
   ```
4. Replace `VIDEO_ID_HERE` with your video ID.

---

## 2. Add a Tableau Visualization (ecuador.html)

1. Go to [public.tableau.com](https://public.tableau.com/app/discover)
2. Find a visualization you like (search: Ecuador, Latin America, economics, etc.)
3. Click **Share → Copy Embed Code**
4. Open `ecuador.html` and find the `<!-- RUBRIC: Tableau embed -->` comment block
5. Replace the placeholder paragraph with the full embed code Tableau gives you

---

## 3. Add Your Images

Place any images you want to use in the `Images/` folder.
The scratch page already references `Images/Quito.jpeg`.

---

## 4. Deploy to GitHub Pages

1. Create a new GitHub repository (public)
2. Upload all these files, maintaining the folder structure
3. Go to **Settings → Pages**
4. Set source to `main` branch, root folder
5. Your site will be live at `https://[yourusername].github.io/[reponame]/`

---

## Rubric Checklist

### Scratch Page (ecuador.html + ecuador.css)
- [x] Ordered list with embedded unordered lists (cities with sub-bullets)
- [x] Image (Quito.jpeg)
- [x] YouTube embed (add your video ID)
- [x] On-page anchor (#top, #video-section)
- [x] Custom background color (warm cream via CSS)
- [x] Custom stylesheet (css/ecuador.css) — NO Bootstrap
- [x] 4+ style definitions in stylesheet
- [x] Font color styles (multiple: --terracotta, --forest, --text-mid, etc.)
- [x] Font family styles (Lora serif + Nunito sans-serif)
- [x] 3+ divs: #header-div, #main-content-div, #article-div, #sidebar-div, #footer-div, #tableau-div
- [x] Tableau embed placeholder (add your embed code)
- [x] Navigation back to professional pages (header-nav)
- [x] Link to webapp.html

### Bootstrap Pages (index.html, resume.html, blog.html)
- [x] Professional Bootstrap 5 theme
- [x] Custom CSS (css/custom.css)
- [x] Navbar with all links
- [x] Professional appearance throughout

### Resume (resume.html)
- [x] HTML résumé (NOT a PDF)
- [x] Education, Experience, Skills, Honors
- [x] Useful, organized information

### Web App (webapp.html)
- [x] AI-assisted creation
- [x] Creative (Ecuador trivia quiz — not a generic generator)
- [x] All styles/HTML/JS in one file
- [x] Linked from scratch page (ecuador.html)
- [x] Interactive and functional

### General
- [x] Professional appearance (no aesthetic errors)
- [x] All links functional (update LinkedIn/email placeholders)
- [x] No broken images (add your own images to /Images/)
- [ ] Hosted on GitHub Pages (deploy per instructions above)
