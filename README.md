# Baraza VR - Release Notes

Public release notes for **Baraza VR**, an Afro-futuristic VR courtroom drama for Meta Quest 3.

**Live page:** https://seedexr.github.io/baraza-releases

## How to update (every time we publish a build)

1. Open `CHANGELOG.md`.
2. Add a new version block at the **top** of the list:
   ```
   ## [0.2.0] - 2026-08-01
   One-line summary of this build (optional).

   ### Added
   - New things players can now do.

   ### Changed
   - Things that were reworked or improved.

   ### Fixed
   - Bugs squashed.

   ### Known Issues
   - Things we already know about.
   ```
3. Commit and push.

The branded page (`index.html`) fetches `CHANGELOG.md` and re-renders automatically. You only ever edit `CHANGELOG.md`.

Use whichever sections apply (`Added`, `Changed`, `Fixed`, `Known Issues`, `Removed`) - empty ones can be left out. Match the version number to the app's `bundleVersion`.
