# Drink Tally — Support & Privacy

Source for <https://vtrantescu-ops.github.io/BeerCounter-Support/>, the Support
and Privacy Policy page that the Drink Tally iOS app and its App Store listing link
to.

- `#support` — Support & FAQ
- `#privacy` — Privacy Policy

`index.html` is a single self-contained page: no build step, no dependencies.
Edit it and push; GitHub Pages redeploys from `main` at the repository root.

Both anchors are referenced from the app's Settings tab and from App Store
Connect, so **the URLs must not change**. Apple requires a reachable privacy
policy URL, and a 404 here blocks review.
