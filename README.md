# Selenium Interview Arcade

An interactive, neon themed landing page for **Selenium WebDriver interview questions for automation testers**. Flip through question cards, track what you have mastered, watch a mini test suite run, and jump to guides and training pages. Pure HTML, CSS and JavaScript with no build step.

## What is inside

The page opens with a hero that cycles through interview topics and a small test runner you can trigger with one click. Below it sit ten flip cards grouped into Basics, Locators, Waits, Frameworks and Grid, with topic filters and a progress bar that remembers your mastered cards in the browser. Further down you will find four linked guides, three linked courses and a full footer. Every card and button is a real, clickable link.

## Three designs, one file

Use the switcher in the header to change the whole look instantly:

- **Arcade** has glowing rounded cards on a deep midnight background.
- **Terminal** is sharp, monospaced and scanline textured.
- **Sticker** uses thick white outlines, hard offset shadows and playfully tilted cards.

Your choice is saved with localStorage, so the page opens the way you left it. The palette uses neon blue, neon pink, neon green, neon yellow and neon purple throughout.

## Run it locally

Download or clone the repository and open `index.html` in any modern browser. No install is needed.

## Publish with GitHub Pages

1. Push `index.html` and `README.md` to the root of your repository.
2. Open **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, then save.
4. After a minute your page is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Customise

All colours live in the `:root` block at the top of the stylesheet. Interview questions are stored in the `Q` array near the end of the file, so you can add or edit cards without touching any layout code. Links are plain anchor tags, so they are easy to change.

## Accessibility and responsiveness

The layout adapts from large desktops down to small phones. Keyboard focus is clearly visible, filter and theme buttons announce their state, and animations switch off for people who prefer reduced motion.

## Links featured on the page

Guides: Selenium WebDriver interview questions, Selenium automation testing roadmap 2026, Selenium automation testing framework beginner guide, and the career guide to becoming a Selenium automation tester.

Courses: Selenium training in Pune, Python training in Delhi and JavaScript training in Delhi.

## Licence

Released under the MIT licence. Use it, remix it and make it your own.
