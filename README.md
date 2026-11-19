# Muhammad Aldi Riansyah: Portfolio

Personal portfolio website (single-page, plain HTML, CSS and JavaScript) for Data Analyst applications.

- **Live site:** https://aldiriansyahhh02.github.io
- **Sections:** About, Projects, Experience & Education, Skills, Contact
- **Language:** English and Indonesian (EN/ID toggle). The page opens in English and remembers the last choice in the browser.
- **Theme:** light and dark mode, following the device setting by default

## Projects

1. Sewa Penginapan Management: Python CRUD application for hotel room management (Python)
2. Tokopedia Efficiency and Retention Analysis: promo efficiency and user retention case study (Python, Pandas, Jupyter Notebook, Tableau)
3. Hotel Booking Demand Machine Learning: hotel booking cancellation prediction (Python, Pandas, Scikit-learn, SHAP, Jupyter Notebook)

Each project card has a one-line business context, my role and approach, the tools used, two or three result numbers, and links to the code on GitHub or the Tableau dashboard.

## Edit

Open `index.html` in a text editor. There is no separate config file.

- Page text: edit the HTML directly in each section.
- Indonesian text: edit the `ID` list in the `<script>` block at the bottom. Each line pairs an English sentence with its Indonesian version, so when you change an English sentence, change its key in that list too.
- Portrait: the photo is embedded in the hero section as a base64 image, so the site is one file. To replace it, embed a new compressed image in the same `<img>` tag.
- Colors: change the variables at the top of the `<style>` block (`--bg`, `--ink`, `--accent` and so on). Dark mode values are in the second group of variables.

## Run locally

Open `index.html` in a browser. No build step or dependencies.

## Deploy

This repository is named `aldiriansyahhh02.github.io`, so GitHub Pages serves it at the address above. Keep `index.html` in the root of the `main` branch, and set **Settings → Pages** to **Deploy from a branch** with `main` and `/ (root)`.
