# Site Plan — Evan Albert Personal Site

## Goal
A simple, fast, one-page personal site for Evan Albert, a senior CS/CSE
undergrad at Ohio State University. Purpose: give recruiters/connections a
quick, credible snapshot (bio, skills, resume, links) — not a full project
portfolio for now.

## Tech / Hosting
- Plain HTML + CSS (+ a few lines of vanilla JS). No framework, no build step.
- Hosted on GitHub Pages via the existing `Evan-Albert.github.io` repo.
- Single page (`index.html`) to start; easy to split into more pages later.

## Page Sections (in order)
1. **Header / nav** — name as logo, links to Résumé (PDF) and Contact anchor.
2. **Hero** — "Hi, I'm Evan Albert" + one-line identity: "Senior CS student
   at Ohio State University."
3. **About** — short bio paragraph (2–4 sentences): what he studies, what
   kind of software/engineering work interests him, what he's looking for
   (internship/new-grad role).
4. **Skills** — compact list/grid of languages, frameworks, tools (grouped,
   e.g. Languages / Frameworks & Tools / Other).
5. **Résumé CTA** — button linking to `/resume.pdf` (placeholder file to be
   dropped in later).
6. **Contact / Links** — email (mailto), GitHub (github.com/Evan-Albert),
   LinkedIn (linkedin.com/in/evan-albert).
7. **Footer** — copyright + repeat of GitHub/LinkedIn links.

Projects section is intentionally omitted for v1 (per your answer) — can be
added as a "Projects" section or page later without restructuring anything.

## Design
- Clean, light/dark aware (reuse `color-scheme`/`theme-color` meta already
  in the boilerplate).
- Single accent color, system font stack (fast, no web-font request).
- Mobile-first responsive layout, generous whitespace, no clutter.
- Accessible: skip link, semantic landmarks, visible focus states — keep
  what the existing boilerplate already does right.

## Content Placeholders (need real values before "done")
- [ ] Final bio paragraph wording (I'll draft; you edit to taste)
- [ ] Skills list (languages/frameworks Evan actually knows)
- [ ] `resume.pdf` file dropped into the repo root
- [ ] Confirm LinkedIn URL (`linkedin.com/in/evan-albert`) is correct
- [ ] Favicon / OG image (optional, can skip for v1)

## SEO / Meta
- Fill in `<title>`, meta description, OG/Twitter tags with real name +
  one-line identity (currently TODO placeholders in index.html).
- Update canonical URL to `https://evan-albert.github.io/`.

## Next Step
Build `index.html` + `styles.css` against this plan, using realistic
placeholder bio/skills text that Evan can quickly edit, then confirm it
renders correctly before pushing.
