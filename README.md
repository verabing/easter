# Easter Nuts

A small Easter calendar for GitHub Pages.

## Concept

- one basket
- five patterned eggs
- one egg unlocks each day from **Maundy Thursday** through **Easter Monday**
- when an egg is opened, it disappears from the basket
- the opened artwork is added to the gallery below
- desktop: images line up next to each other
- mobile: images stack vertically

## Structure

- `index.html` → single-page calendar in English
- `bilder/` → artwork files for the five days
- `reminders/` → small planning notes
- `bakgrunn.jpg` → optional background asset
- `favicon.ico` → site icon

## Replace the placeholder art

The gallery uses these files:

- `bilder/artwork-1.svg`
- `bilder/artwork-2.svg`
- `bilder/artwork-3.svg`
- `bilder/artwork-4.svg`
- `bilder/artwork-5.svg`

You can replace them with your own files and keep the same names, or update the file paths directly in `index.html`.

Recommended image size:

- width: **1200–1600 px**
- format: **jpg** or **webp**
- target file size: **100–400 KB**

## Dates

The current setup uses these dates in `index.html`:

- 2026-04-02 → Maundy Thursday
- 2026-04-03 → Good Friday
- 2026-04-04 → Holy Saturday
- 2026-04-05 → Easter Sunday
- 2026-04-06 → Easter Monday

Change them in the `items` array if you want another Easter year.

## Publish on GitHub Pages

1. Create a new repository.
2. Upload the files from this folder.
3. In GitHub, open **Settings → Pages**.
4. Set source to **Deploy from a branch**.
5. Choose the `main` branch and `/root`.
6. Save.

## Notes

This version is intentionally simple:

- no frameworks
- no libraries
- no language switcher
- no build tools
