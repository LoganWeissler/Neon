# Neon Recall

Neon Recall is a dependency-free browser study game. Questions descend toward a defense core; choose the right answer before impact. Wrong choices increase the descent speed, and three base hits end the level.

## Run locally

```bash
npm run dev
```

Open `http://localhost:5173`.

## Create a custom level

Select the import control in the lower-right corner or press `I`. You can:

- upload a PNG, JPG, or WEBP photo for local OCR;
- upload TXT, Markdown, or CSV notes;
- paste notes directly.

For the strongest multiple-choice generation, use clear facts such as `FTP uses port 21` or `Capital of France: Paris`. Other complete sentences become true-or-false questions. Photo text recognition and question generation both run in the browser.

## Controls

- `1`–`5`: choose an answer
- `I`: import notes
- `M`: mute or unmute effects
- `Esc`: close the importer

## Production build

```bash
npm run build
npm run preview
```

The static site is written to `dist/`.

## Publish with GitHub Pages

Upload the project files to a GitHub repository, then open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and `/(root)` folder, and save. GitHub will display the public site URL after deployment finishes.
