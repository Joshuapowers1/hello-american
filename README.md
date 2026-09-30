# Hello American

**An independent design concept. Not an official website.**

> **Important notice.** Hello American is a personal, educational project by Josh Powers. It is **not affiliated with, endorsed by, sponsored by, or connected to** America.gov, the U.S. General Services Administration, the National Design Studio, or any U.S. government agency. It uses no government seal, logo or branding. It is not legal, tax, medical, financial or immigration advice. Do not use it to make real decisions. Always confirm fees, dates and rules on the official .gov page linked in each answer.

## What this is

A weekend-sized experiment that asks one question: what would a government help page feel like if it were built for speed, plain words and proof?

It is a single-page app with:

- A greeting and one search box, with fuzzy matching that forgives typos
- 40 answers, each with what you will need, numbered steps, the most common mistake, and links to the official .gov sources they were compared against
- Answers labeled "Checked" (compared with the cited pages on Sept 30, 2026) or "Draft" (written by an AI and marked unverified)
- English, Spanish, Chinese, Vietnamese, Tagalog and Arabic (right to left)
- Keyboard-first use, light and dark themes, high contrast, adjustable text size, reduced motion, read aloud
- A privacy policy, terms, accessibility statement, FAQ and feedback form

## Educational takeaways

These are my opinions as a student builder, based on public pages I viewed on September 29 and 30, 2026. Things change, and I may be wrong or out of date. Corrections are welcome: open an issue.

1. **Put the task first.** The fastest help page is a greeting and a search box. Anything between a person and their question needs to earn its place.
2. **Show the source on every answer.** People can spot look-alike sites when they can see the real web address and finish on the official page.
3. **Label what an AI wrote.** A draft from a model is useful but must be marked unverified, with no official source implied.
4. **Say what you save.** A short plain-language privacy page beats long, hard-to-find legal text.
5. **Only show what works today.** Mockups of future features can set the wrong expectation.
6. **Accessibility is a feature list, not a footnote.** Pause controls, visible focus, contrast and text size should be built in from the start.

## Try it

- Live concept: https://claude.ai/artifact/Mu6fPHeMpmBd615VzyAb1a
- The site I compared against: https://america.gov

## Files

- `index.html` is the complete page, built from `shell.html` (markup and styles) and `app.js` (logic and data)
- `lang_*.json` hold the translations, loaded on demand
- No build step. To run locally, serve the folder with any static server, for example `python3 -m http.server`

Features that need the Claude artifact runtime, such as AI drafts and saving feedback, only work on the published page. When run locally, those parts are unavailable and the checked answers still work.

## Facts and sources

Every answer cites official sources. Fees, deadlines and rules change. If you find a wrong fact or a broken link, please open an issue with the answer name and the correct source.

## License

MIT. See `LICENSE`. The license covers this code only. It does not grant any right to use government names, seals or logos.
