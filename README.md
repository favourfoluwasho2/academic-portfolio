# Foluwasho Favour — Academic Portfolio & Student Management Platform

A 5-page personal academic portfolio built with plain HTML, CSS, and JavaScript.

**Student:** Foluwasho Favour
**Matric No.:** 2025/B/CSC/0651
**Department:** Computer Science
**Email:** f.foluwasho3222@miva.edu.ng

## Pages
- `index.html` — Homepage (photo/avatar, welcome message, nav, bio, video)
- `about.html` — Education, career aspirations, technical skills, hobbies
- `projects.html` — Three featured projects with descriptions and links
- `planner.html` — Interactive academic planner (add / complete / delete tasks)
- `contact.html` — Contact form with live JavaScript validation

## Structure
```
/
├── index.html
├── about.html
├── projects.html
├── planner.html
├── contact.html
├── css/
│   └── styles.css
├── js/
│   ├── script.js      (shared: nav toggle, footer year, skill bars)
│   ├── planner.js      (task management system, saves to localStorage)
│   └── contact.js      (form validation)
└── README.md
```

## Before you submit
1. **Replace the photo:** the homepage currently shows an "FF" monogram avatar
   in place of a real photograph. Swap it for an `<img>` of yourself in
   `index.html` (search for `class="avatar"`).
2. **Replace the demo video:** `index.html` embeds a placeholder sample clip.
   Swap the `<source src="...">` in the "Featured Media" section for your own
   uploaded video file or a YouTube embed.
3. **Update project links:** `projects.html` has one placeholder link marked
   "internal cohort project" — replace with a real or simulated link if you
   have one.

## How to host it for free (GitHub Pages)
1. Create a new GitHub repository, e.g. `academic-portfolio`.
2. Upload all files in this folder (keep the `css/` and `js/` folders intact).
3. On GitHub: **Settings → Pages → Source → Deploy from branch → `main` /
   root**. Save.
4. Your site will be live at:
   `https://<your-github-username>.github.io/academic-portfolio/`
5. Submit both links:
   - Live site: the GitHub Pages URL above
   - Repository: `https://github.com/<your-github-username>/academic-portfolio`

## Notes on requirements coverage
- **Semantic HTML:** `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
- **Forms:** contact form (`contact.html`), planner task form (`planner.html`)
- **Tables:** education/certifications table (`about.html`)
- **Images:** avatar/monogram graphic, project media placeholders
- **Multimedia:** `<video>` element on the homepage
- **Hyperlinks & lists:** navigation, footer links, hobby list, project tags
- **CSS:** external stylesheet, Flexbox + Grid, responsive nav, hover/scroll
  animations, single consistent colour system, mobile breakpoints
- **JavaScript:** event handling, DOM manipulation, array-based task CRUD,
  localStorage persistence, form validation (empty fields, email regex,
  digits-only phone number), dynamic stat counters
