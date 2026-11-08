# BrewSim

A realistic craft brewery management game set in Ottawa–Gatineau, from 1985 to 2040. Design recipes, brew with real beer chemistry, run a taproom and grow a microbrewery. English and French.

*En français :* un jeu réaliste de gestion de microbrasserie à Ottawa–Gatineau, de 1985 à 2040. Le jeu est bilingue.

**Play:** https://www.davidpepin.ca/brewsim/

## How this repository works

This repository only holds the **published build**: `index.html` is the whole game in one file (about 7 MB with its fonts, sounds and illustrations). Nothing to install. You can also download the file and open it locally.

The source code (TypeScript engine, game data, tests and the Vite build) lives in a separate working folder. To publish a new version:

1. In the source folder, run `npm run build`. It writes the single-file game to `dist/brewsim.html`.
2. Copy `dist/brewsim.html` here as `index.html`, commit and push.

Keep `og-image.jpg` (the preview image shown when the link is shared on social media) in place; the build doesn't produce it.

The source `index.html` already contains the Google Analytics tag, so it carries over to every build.

## Credits

Design, research and direction: David Pépin. Coded with Claude (Anthropic). Illustrations generated with ChatGPT (OpenAI). Full credits (sounds, typefaces, icons, data sources) are on the in-game Credits page. Part of [davidpepin.ca/projects](https://www.davidpepin.ca/projects/).

The published page loads Google Analytics (page views only, same property as davidpepin.ca). The tag only runs on davidpepin.ca, not when you open the file locally.
