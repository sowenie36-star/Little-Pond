# Samara Shyle’s Pond

A standalone static site with five ducks and four photo memories. The fifth duck opens the full gallery.

## Preview
From this folder run `python3 -m http.server 8000`, then open http://localhost:8000. No packages or build step are needed.

## Deploy to Vercel
Unzip the package. Put all contents of this folder in your project root: index.html, styles.css, script.js, vercel.json, and assets/. Replace the old entry point; do not deploy just index.html.
Use Framework Preset: Other, an empty Build Command, and Output Directory: `.`. Set the project's Root Directory to the folder containing these files. The included vercel.json specifies static output. Commit/upload all files and deploy a new production version.

## Editing
- index.html: headings, instructions, semantic structure
- styles.css: responsive layout, focus and reduced-motion styles
- script.js: duck sequence, gallery, synthesized audio, pond canvas
- assets/: four optimized photo memories

Sound starts only after opting in. Missing photos display a message without blocking the game. Photos are served locally with no external services or tracking.
