# NORTH CUT

A fictional barbershop landing page built with plain HTML, CSS, and vanilla JavaScript. It is a portfolio demonstration: the prices, hours, and shop identity are illustrative, there is no real shop address or business phone number, and no appointments are accepted.

## Project structure

```text
.
├── index.html       # Page content and metadata
├── css/
│   └── styles.css   # Responsive layout and visual styles
├── js/
│   └── main.js      # Mobile navigation and current footer year
└── README.md        # This guide
```

## Run locally

No build step or package installation is needed.

1. Download or clone this project.
2. Open `index.html` in a browser.

For a local HTTP server, run `python -m http.server 8000` from the project directory, then open <http://localhost:8000>.

## Deploy with GitHub Pages

1. Create a GitHub repository and add these project files to its root.
2. Push the files to the repository's default branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the default branch and the `/(root)` folder, then save.
6. Wait for the Pages deployment to finish. The site URL will appear in the Pages settings.

The site uses relative paths for its stylesheet and JavaScript, so it works from either a user/organization Pages root or a project Pages subpath.

## Images and external services

The gallery and hero use image URLs hosted by Unsplash. They are subject to the [Unsplash License](https://unsplash.com/license); confirm the current license terms before reuse in a commercial project. Google Fonts are loaded remotely. The WhatsApp link opens a prefilled message flow without a phone number; the visitor must choose a recipient, and no real booking service is connected.
