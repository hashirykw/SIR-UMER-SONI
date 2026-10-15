# Sir Umer Soni · Biology Enclave website

A multi-page website for Sir Umer Soni (O Level Biology 5090 and IGCSE Biology 0610). Every page is one self-contained HTML file, and all files sit in one flat folder, with no asset sub-folders.

## Files

| File | What it is |
|---|---|
| `index.html` | Home: microscope-lens hero, diagram-first scroll story, courses, 19-topic slide box, study tools, Instagram/Facebook |
| `courses.html` | O Level 5090 (four papers), 3-month O Level course, IGCSE 0610 Core vs Extended, ways to learn |
| `syllabus.html` | All 19 (5090) and 21 (0610) topics with sub-topics, filters, search, a progress ring and a definition for each topic |
| `past-papers.html` | 5090 and 0610 question papers + mark schemes (2016–2026), tracker with scores, exam timer with focus mode |
| `lab.html` | Bio Lab: label-the-cell quiz, Punnett squares, magnification calculator, enzyme temperature/pH simulator, definition flashcards and quiz |
| `notes.html` | Notes store with cart and WhatsApp checkout |
| `about.html` | About Sir Umer |
| `contact.html` | Enrolment form that opens WhatsApp, contacts, FAQ |
| `404.html` | Not-found page |
| `umer-soni.webp` | Portrait cutout (transparent background) |
| `umer-soni.jpg` | Share image for WhatsApp/social previews (1200×630) |
| `vercel.json`, `robots.txt`, `sitemap.xml` | Hosting and search files |

## Before going live: change these

1. **WhatsApp number.** Search any page for `const WA=` and set Sir Umer's own number (country code, no `+` or spaces), plus `WA_DISPLAY`. It is currently the Cambridge Online / SWK admissions number, +92 346 3311647. The footer and contact page links use the same number, so search for `923463311647` and replace every occurrence.
2. **Notes prices and titles** are demo values. Search for `PRODUCTS` in any page.
3. **3-month course week plan** (Courses page) is labelled as an example plan. Replace it with the real schedule.
4. **Domain.** `sitemap.xml`, `robots.txt` and the page `<head>` use `https://sirumersoni.vercel.app`. Change these if you use another domain.

Because every page carries its own copy of the shared code, a change like the WhatsApp number has to be made in every HTML file. Find-and-replace across the folder does this in one go.

## Deploy

- **Vercel:** drag the folder into vercel.com/new, or run `vercel` inside it. `vercel.json` gives clean URLs (`/lab` instead of `/lab.html`).
- **Netlify / GitHub Pages / any host:** upload the folder as is. No build step is needed.

## Notes

- Progress (tracker, ticked topics, known definitions, cart, theme, sound) is saved in the visitor's own browser only.
- Past papers open from PapaCambridge. A few recent or rare variants may not be uploaded there yet.
- Libraries load from CDNs: GSAP, Lenis and Three.js. Fonts: Unbounded, Hanken Grotesk, IBM Plex Mono.

## Sources

- Cambridge O Level Biology 5090 syllabus 2026–2028: https://www.cambridgeinternational.org/Images/697330-2026-2028-syllabus.pdf
- 5090 syllabus update: https://www.cambridgeinternational.org/Images/724260-2026-2028-syllabus-update.pdf
- Cambridge IGCSE Biology 0610 syllabus 2026–2028: https://www.cambridgeinternational.org/Images/697203-2026-2028-syllabus.pdf
- Sir Umer Soni's public Instagram (@umer.q.soni) and Facebook (sirumersoni) pages
