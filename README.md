# Victoria Todd - Website

## Editing Guidelines

The following pages are edited directly:
- /about-me (about-me.astro)

Content is added to the following pages via their respective JSON file:
- /home (home.json) - Gallery Layout
- /concept-art (concept-art.json) - Project Layout
- /illustration (illustration.json) - Project Layout
- /2d-animation (2d-animation.json) - Project Layout
- /storyboarding (storyboarding.json) - Slideshow Layout

## Robots.txt, Sitemap.xml

Both of these files are generated automatically upon building.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
