
# VentureVerse 2026: Event Landing Page

Designed by **Diya Singh, 26CSE180**.
Single-page landing page for a fictional EDC JSSUN event, built for the Technical Team Recruitment 2026 (Task 01, First-Year).

## How to view
1. Download or clone this folder.
2. Open `index.html` in any browser. No install or build step is needed.
(An internet connection is only used to load Google Fonts; without it the page falls back to system fonts.)

## Files
- `index.html`: page structure (header, hero with countdown, about, schedule, speakers, register, contact, design credit, footer)
- `style.css`: all styling, with colour and font tokens at the top
- `script.js`: mobile menu, countdown, and demo registration form
- `glass-hero.js`: animated glass effect on the hero headline (WebGL2)
- `vapor-countdown.js`: the particle countdown (Canvas 2D)
- `assets/`: EDC logo (plus a light version for the dark theme), hero background image and speaker images

## Features
- **Countdown:** a band just below the hero counts down (days, hours, minutes, seconds) to 12 Nov 2026, 10:00 AM IST. 
- **Demo registration form:** checks that every field is filled and the email format is valid, then shows a confirmation. It is a demo, so no data is saved or sent.
- **Mobile menu:** below 768px the navigation collapses into a Menu button.
- **Glass headline:** the hero title is real text; a WebGL2 canvas paints refractive glass over each word, and the light follows the mouse. If WebGL2 is unavailable or reduced motion is on, it falls back to the plain headline or a still frame.
## Credits
- EDC logo: provided by EDC JSSUN in the task brief.
- Hero background image: supplied by the applicant (AI-generated image provided by the applicant for this task).
- Fonts: Bricolage Grotesque and Figtree via Google Fonts.
## AI disclosure
I used Claude (Anthropic) to plan the page, generate the first draft of the code, and port the glass headline effect from React to plain JavaScript. I reviewed it, tested the features, and can explain each part.
Also used dribble and 21st
