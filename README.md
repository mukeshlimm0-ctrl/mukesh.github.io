# Mukesh Limbu — CET138 learning portfolio

A static ePortfolio for CET138 Full Stack Development Assignment 1. The portfolio covers all five required topics with explanations, code samples, and working in-browser demonstrations:

1. Full-stack development — animated request-flow model
2. HTML — native form validation
3. CSS — interactive custom-property playground
4. Bootstrap — responsive Bootstrap 5 grid and cards
5. JavaScript — add-and-complete practice checklist

## Project files

- `index.html` — page content and interactive JavaScript
- `style.css` — responsive layout, light/dark themes, animations, and Bootstrap offline fallbacks

Upload **both files to the same folder** in your GitHub repository. The relative stylesheet link in `index.html` expects `style.css` beside it.

## Run locally

Open `index.html` in a modern browser or serve this folder with any static web server. There is no build step or back-end service. The Bootstrap example loads Bootstrap 5.3.3 from jsDelivr; small fallback styles keep it readable if the CDN is blocked. The light/dark selection is remembered in the browser when storage is available. The five topics open one at a time as slide-style dialogs from the navigation, with Previous/Next and Back controls, instead of being stacked for page scrolling. A topic's **Open example** button opens its existing interactive demo in a second dialog without duplicating the controls.

## Publish a public URL with GitHub Pages

1. Sign in to GitHub and create a **public** repository named `mukesh-limbu-portfolio` (or choose another name).
2. Upload **both `index.html` and `style.css`** to the repository's top-level folder and commit them to the `main` branch. You may upload this `README.md` too.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**. Choose **main** and **/(root)**, then press **Save**.
5. Wait for GitHub Pages to finish its first deployment. The public address will follow this pattern:

   `https://YOUR-USERNAME.github.io/mukesh-limbu-portfolio/`

Replace `YOUR-USERNAME` with the GitHub account name that owns the repository. GitHub Pages may take a short time to make the first deployment available. If you choose a different repository name, use that name in the URL instead.

> The URL pattern above is a template, not a live published URL. A real public GitHub Pages link exists only after the repository is created and Pages is enabled.

## Accessibility and implementation notes

- Semantic landmarks, headings, labels, visible focus states, and live status messages are included.
- CSS animations respect `prefers-reduced-motion`.
- The site uses plain HTML, CSS, and JavaScript, so GitHub Pages can host it without a build system.
- The task list and goal form are browser-only examples; they do not send or persist data to a server.
