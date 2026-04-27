# La Dictée de la Silicon Valley — Project Notes

## What this is
Static website for "La Dictée de la Silicon Valley 2026", a French spelling competition event organized by the Breil family as a non-profit community initiative.

## Deployment
- **GitHub repo:** https://github.com/nbreil/ladictee_gsite
- **GitHub Pages URL:** https://nbreil.github.io/ladictee_gsite/
- **Deploy:** every push to `main` auto-deploys via GitHub Pages
- **Build:** no build step — pure static HTML/CSS/JS, served from root

## Site structure
| File | Page |
|---|---|
| `index.html` | Home — hero, schedule, awards, sponsors |
| `register.html` | Register — Google Form iframe placeholder |
| `contact.html` | Contact — Google Form iframe placeholder |
| `about.html` | About — bilingual story + team |
| `style.css` | All shared styles |
| `main.js` | Mobile menu toggle + active nav link |

## Design
- **Fonts:** Cormorant Garamond (headings) + Jost (body) via Google Fonts
- **Colors:** navy `#1a2f5a`, French blue `#0055A4`, French red `#EF4135`, cream `#F7F4EF`
- **Theme:** French school notebook ("cahier de dictée") — ruled lines pattern in hero, red margin line
- **Tricolor bar** runs along the top of the nav and footer

## Content
- **Event date:** Saturday March 21st, 2026, 10:00 AM – 12:00 PM
- **Location:** French American School of Silicon Valley (Upper Campus), 220 Blake Ave, Santa Clara, CA 95051
- **Contact email:** info@ladictee.org
- **Original Google Site:** https://sites.google.com/view/ladictee2026

## Team (About page)
- Nicolas Breil — Founder
- Amel Breil — Co-Founder & Sponsorship
- Adam Breil — Communication
- Selma Breil — Chief Inspiration Officer

## Sponsors
Alliance Française Silicon Valley, French American School of Silicon Valley, Clairefontaine, Lireka, FrenchBee, Gourmet Corner, Maison Alyzée, Brioche Pasquier, Bay Road Story Studio

## TODO / Next steps
- [ ] Add Google Form embed URLs to `register.html` and `contact.html` (see iframe comment blocks)
- [ ] Replace sponsor text cards with actual logo images
- [ ] Optional: add French translation page (`accueil.html`) for the "Accueil (FR)" nav link
- [ ] Optional: replace hero CSS background with a real event photo
