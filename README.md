# From Fridge to Fork

A playful recipe-finding website for students and anyone cooking with ingredients they already have.

## What it does

- Select ingredients by tapping, searching, or using food categories.
- Arrange ingredients in a red retro fridge with desktop drag-and-drop or touch dragging.
- Find recipes that match at least two stocked ingredients.
- Filter by meal, ready-to-cook recipes, time, student meals, and healthy picks.
- Save favourite recipes and fridge contents in the browser using localStorage.
- Open 228 recipes with quantities, equipment, cooking steps, and timing details.
- Use a responsive phone layout with larger touch controls and full-screen recipe details.

## Files

- `index.html` — semantic page structure and interface.
- `styles.css` — layout, typography, colours, responsive rules, and animations.
- `app.js` — recipe data, ingredient matching, filters, saved state, and interactions.
- `assets/` — photographic-style food pictures, ingredient illustrations, fridge artwork, and fonts.
- `licenses/` — font license notices.

There is no build step, paid API, database, or login. Keep the files and folders together. Open `index.html` in a browser, or serve this folder using a local static server.

## Publish with GitHub Pages

1. Upload all project files, with `index.html` at the repository root.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose **main** and **/ (root)**, then save.
5. Open the public URL displayed by GitHub after deployment completes.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Design and technology

Built with HTML, CSS, and vanilla JavaScript. The visual direction combines a red retro fridge, mint gingham, Fraunces headings, Manrope interface text, and transparent photographic-style food images. State is stored on the current device; there is no account or server-side data storage.

## AI use

AI tools assisted with coding, image generation, design exploration, copy revisions, and testing. The project creator guided the concept, audience, content preferences, and iterative design decisions. Food pictures are AI-generated photographic-style images. This overview can support the project's required AI-use explanation; the submission should also include the creator's own process and reflection.

## Validation

The core selection, recipe matching, filters, saved state, and recipe dialogs were checked. Browser previews were tested at 320, 375, 390, 430, 768, 844, and 1440 pixels, including touch dragging and landscape layout.

## Fonts

Fraunces and Manrope are included under the SIL Open Font License 1.1. Their notices are in `licenses/`.
