# Publish Arcplan for free

Arcplan is a static browser application. It needs no server or database.

## GitHub Pages

1. Create a public GitHub repository, for example `arcplan`.
2. Upload `index.html`, `styles.css`, `app.js`, and `icon.svg` to the repository root.
3. Open **Settings > Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will provide a public HTTPS address such as `https://username.github.io/arcplan/`.

Anyone can open that address in a browser without an account or installation.

## How saving works

- Every change is saved automatically in that browser's local storage.
- Local data stays on that device and browser profile; it is not uploaded anywhere.
- **Save project file** downloads a portable `.json` project file.
- **Export > Open project** restores that file on another device.
- Clearing browser/site data removes the local copy, so important projects should also be saved as project files.
