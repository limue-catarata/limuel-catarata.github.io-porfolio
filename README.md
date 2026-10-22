# Limuel Catarata — Personal Portfolio

A responsive personal portfolio website featuring the Smart Fish Drying Monitoring System capstone project, a featured game link, and email contact.

## Project contents

- `index.html` — portfolio page, styling, and JavaScript interactions
- `images/profile.jpg` — profile photo used in the About Me section
- `README.md` — this setup and deployment guide

## Features

- Responsive layout for desktop and mobile
- Section navigation and mobile menu
- About Me / profile photo section
- Smart Fish Drying Monitoring System capstone overview
- Featured game project linking to [https://lbs-vyo1.onrender.com/](https://lbs-vyo1.onrender.com/)
- Contact links for `limuelruiz21@gmail.com`
- Scroll-in animations with reduced-motion support

## Run locally

1. Extract the ZIP file.
2. Open the extracted `pasil_fishdrying_portfolio` folder.
3. Double-click `index.html` to open it in a browser.

For a local development preview in Visual Studio Code, open the folder and use a local preview extension or a simple local HTTP server.

## Publish with GitHub Pages

1. Create or open your GitHub repository.
2. Upload the **contents** of the `pasil_fishdrying_portfolio` folder (including `index.html`, `images/`, and `README.md`) to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under the build/deployment settings, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. Wait for deployment to finish and open the published URL shown in the Pages settings.

If you already use a repository that serves the portfolio, back up its current files before replacing them.

## Link behavior

- **Play My Game** opens the supplied game link in a new tab.
- **Message me on Gmail** opens Gmail's compose window with `limuelruiz21@gmail.com` as the recipient. If Gmail is not signed in, the browser may ask you to sign in.
- Navigation buttons scroll to their matching sections.
- The game itself is hosted separately; this portfolio links to it rather than controlling its gameplay.

## Customization

- Update the biography and project descriptions in `index.html`.
- Replace `images/profile.jpg` with your preferred profile image while keeping the same filename, or update the image path in the HTML.
- Keep filenames and folder capitalization consistent for GitHub Pages.

## Notes

This is a static website. A contact button opens an email draft; it does not send email automatically. The capstone dashboard and monitoring content are a portfolio presentation, not a live-connected IoT system unless separately implemented and connected.
