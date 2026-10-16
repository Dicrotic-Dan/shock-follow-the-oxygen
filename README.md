# Shock · Follow the oxygen

Built by Dan Howard, Dicrotic.

An animated teaching model of the circulation in shock. Pick one of nine phenotypes, apply interventions, and watch mean systemic filling pressure, venous return, cardiac output, oxygen delivery and extraction change, along with a simulated Swan–Ganz panel. Values outside normal ranges are flagged. "Zoom into this capillary bed" opens a second page showing delivery, shunting and extraction at the level of the capillaries and cells.

Try it: https://shock-circulation.web.app

## Running it

There's nothing to install or build. Download the repo (green **Code** button → **Download ZIP**), unzip it, and open `index.html` in a browser.

- `index.html` is the main page (the whole circulation)
- `shock-microcirculation.html` is the capillary close-up

Keep both files in the same folder with these names. The zoom buttons link to each other and pass the current patient along in the URL. Neither file loads anything from the internet, stores anything or collects data. To host it, upload both files to any static web host (GitHub Pages, Netlify, Firebase Hosting, a school web server).

## Changing it

Each page is a single HTML file with its CSS and JavaScript inline, so a text editor is all you need. The model's assumptions, equations and references are in the "How the model works, and where it stops" section at the bottom of the main page. You're welcome to adapt the cases, retune the physiology, translate it or build it into your own teaching.

## License

© 2026 Dan Howard. Licensed under [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/) (CC BY-NC 4.0). Full text in [LICENSE](LICENSE).

In short, you may copy, share, change and build on this, as long as you:

- **Give credit:** "Shock · Follow the oxygen, by Dan Howard (Dicrotic)", with a link to this repo, and say if you changed it.
- **Don't use it commercially:** no selling it, putting it behind a paywall, or using it in a paid product or course.

For commercial use, ask first.

## Not for clinical use

This is a qualitative teaching model, not a clinical decision tool. Don't use it to make decisions about real patients.
