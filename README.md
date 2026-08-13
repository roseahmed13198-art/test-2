# THE CHEFZ – Working Hours Update Site

Static landing page for THE CHEFZ Working Hours updates.

## Project structure

```text
THE-CHEFZ-Working-Hours/
├── index.html
├── style.css
├── book-icon.png
├── calendar-days.svg
├── chart.png
├── chevron-right.svg
├── clock.png
├── gear.png
├── logo.png
└── phone-mockup.png
├── .gitignore
├── .nojekyll
└── README.md
```

## Current links

- **Inform Us with New WHs:** Google Apps Script request form is connected in `index.html`.
- **Learn How to Change WHs:** not connected yet; the button is intentionally disabled until the instructions page/PDF/video is ready.
- **Email:** `rose.ahmed@thechefz.co`
- **WhatsApp:** `+20 10 44564470`

## Run locally

No build tools are required.

Open `index.html` directly in a browser, or use the **Live Server** extension in Visual Studio Code.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload/push all files and folders from this project.
3. In GitHub, open **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`.
6. Save and wait for GitHub Pages to publish the site.

## Updating the future instructions link

When the instructions page/PDF/video is ready, replace the disabled `<span class="cta cta-disabled">...</span>` in `index.html` with an `<a>` element and add the URL.


Arabic mode mirrors the desktop composition (left/right) while preserving natural RTL text flow.
