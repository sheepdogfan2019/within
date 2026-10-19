# With(in)

A daily hidden-word puzzle, packaged as an installable web app (PWA). It's all static files: no server or database.

## Files
- `index.html` – the game, with all 330 clues built in
- `manifest.webmanifest`, `icons/` – app name, colors and home-screen icons
- `sw.js` – lets the game load offline and update itself

## Put it online with GitHub Pages
1. Upload everything in this folder to the root of a public GitHub repository, keeping the `icons` folder.
2. In the repository, go to Settings > Pages, choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
3. After a minute the game is live at `https://<username>.github.io/<repo>/`.

## Installing it on a phone
- iPhone: open the site in Safari, tap Share, then "Add to Home Screen".
- Android: open the site in Chrome and tap "Install app" (or menu > Add to Home screen).

## Feedback
Each puzzle has an "Email feedback on this clue" link that opens a pre-filled email to sheepdogfan2019@gmail.com with the date, level and clue (and the answer, once the puzzle is finished). The address is also shown with a Copy button for phones without a mail app set up.

## Updating the game
Replace `index.html`, then open `sw.js` and change `VERSION` (for example to `within-v2`). Returning players get the new version the next time they open the app.
