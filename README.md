# Interactive Tutorials

Self-paced, adaptive math and physics tutorials for General College Physics, published with GitHub Pages.

- Catalog page: `index.html`
- Each tutorial: `lessons/<folder-name>/index.html` (one self-contained file, no external libraries)
- Math tutorials: `lessons/math-<topic>/` (for example `lessons/math-algebra-basics/`)
- Physics tutorials: `lessons/phys-chNN-<topic>/`, with chapter numbers from OpenStax *College Physics 2e*
- Tutorials store nothing and send nothing; progress lives only in the open browser tab.

## Adding a tutorial

1. Upload the new folder (containing its `index.html`) into `lessons/`.
2. Paste its catalog card into `index.html` below the matching line:
   `ADD NEW MATH TUTORIAL CARDS BELOW THIS LINE` or `ADD NEW PHYSICS TUTORIAL CARDS BELOW THIS LINE, IN CHAPTER ORDER`.
3. Commit. The site updates in about a minute.

## Accessibility

Every tutorial is built to WCAG 2.1 AA: full keyboard use with visible focus, screen-reader-friendly math,
4.5:1 text contrast, nothing shown by color alone, no time limits, and a layout that reflows down to 320 px wide.
