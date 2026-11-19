# Pankti Shah: interior design portfolio

Live site: **[pankti1305.github.io](https://pankti1305.github.io)**

A single-page portfolio with an interactive 3D hero (three.js) that rebuilds the stacked-room artwork from Pankti's portfolio cover. Drag to turn the rooms, scroll to pull them apart, and use the lamp button to switch between day and night lighting.

## Structure

- `index.html`: the whole site (styles, project content and 3D scene)
- `images/`: project photos and drawing sheets

## Editing

- **Project links:** the `PROJECT_LINKS` block at the top of `index.html`
- **Project text and images:** the `PROJECTS` list near the bottom of `index.html`
- **Project pages:** every entry in `PROJECTS` opens on its own page from the Selected work index, at `/#<id>` (for example `/#lushe-glow`). A new entry gets its page automatically.
- **Intro:** on a fresh load the camera moves into a floor plan and the name is signed in before the homepage appears (about 3 seconds). It is the `#intro` block at the top of `<body>` (the plan is an inline SVG, 1 unit = 1 cm), the "intro" section of the CSS, and the script right after the block. It is skipped for reduced motion, and a click, tap or key press skips it.

Changes go live a minute or two after pushing to `main`.
