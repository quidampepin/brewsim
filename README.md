# BrewSim

**A realistic craft brewery management game set in Ottawa–Gatineau, from 1985 to 2040.**
*Un jeu réaliste de gestion de microbrasserie à Ottawa–Gatineau, de 1985 à 2040.*

Lease a space, buy a brewhouse, design recipes with real brewing chemistry, pour in your taproom, sell to bars and stores, and grow, from the pioneer brewpubs of the 1980s to the craft boom and beyond. English and French.

**▶ Play:** open `index.html` (or `brewsim.html`) in any modern browser.

---

## What's in the game

- **Real brewing.** Recipes are calculated like brewing software does: gravity, bitterness, colour, attenuation, against the BJCP 2021 style guidelines. Each batch tastes a little different, and quality control tells you why.
- **A living market.** Drinkers, critics and rival breweries react to what's in the glass. Ratings, trends and prices shift by era.
- **Real money.** Double-entry books, excise duty and provincial beer taxes, loans and cash flow.
- **Eras and scenarios.** Start in any year from 1985 to 2040, or play one of 14 scenarios, from a 1986 pioneer brewpub to the 2020 pandemic.
- **Your brand.** 13 label styles, 20 palettes and 32 emblems; every beer gets its own can and label, in its real colour.
- **Barrels, bottle conditioning and release days.**
- **Help when you need it.** A first-steps guide, screen tips, autoplay, autosave and save slots.

## Hosting it yourself

The whole game is **one self-contained file** (about 7.5 MB): code, fonts, sounds and illustrations are all embedded. It needs no server, no build step and no internet connection once loaded.

1. Copy `brewsim.html` to your site, for example as `brewsim/index.html`.
2. That's it. On GitHub Pages it works as a plain page; no Jekyll front matter is needed.

**Saves stay in each player's browser** (IndexedDB), never on the server. Players can export a save to a file and import it elsewhere from the *Saved games* panel. Nothing is tracked or sent anywhere.

## Credits

- **Design, research and direction:** David Pépin
- **Code:** written with Claude (Anthropic)
- **Illustrations:** 40 painted images generated with ChatGPT (OpenAI) from prompts written for this game
- **Typefaces:** Fraunces, Inter, Oswald, Zilla Slab and Yellowtail, SIL Open Font License 1.1 (via Fontsource)
- **Icons:** Lucide (ISC licence)
- **Sounds:** Wikimedia Commons. The CC BY 3.0 sounds are by Subhashish Panigrahi (stamp), Staile (can) and Joe Lamb (sad trombone). The CC BY-SA 3.0 sound is by Amada44 (bottle; modified, shared under the same licence). The others are public domain or CC0.
- **Data:** BJCP 2021 Beer Style Guidelines; Statistics Canada; Bank of Canada; Canada Revenue Agency; Revenu Québec; Ontario Ministry of Finance; AGCO and RACJ; City of Ottawa and Ville de Gatineau water reports; Palmer & Kaminski, *Water*; maltster, hop grower and yeast lab data sheets. Prices, wages, market behaviour and everything after 2026 are estimates.

The full list, with links to every source and licence, is on the in-game **Credits** page.

Breweries, bars, people and competitions in the game are fictional, except the Members of Barleyment homebrew club, which is real; its members and events here are invented. **Please drink responsibly.**

---

## En français

**BrewSim** est un jeu de gestion de microbrasserie à Ottawa–Gatineau, de 1985 à 2040. Louez un local, achetez votre salle de brassage, créez vos recettes avec une vraie chimie du brassage, servez au salon, vendez aux bars et aux magasins, et faites grandir votre brasserie. Le jeu est entièrement bilingue.

**Pour jouer :** ouvrez `index.html` (ou `brewsim.html`) dans un navigateur récent. Le jeu tient en un seul fichier : aucun serveur, aucune installation. Les parties sont sauvegardées dans le navigateur de chaque joueur et peuvent être exportées dans un fichier.

Conception et direction : David Pépin. Code : écrit avec Claude (Anthropic). Illustrations : générées avec ChatGPT (OpenAI). Le générique complet se trouve dans le jeu.

© 2026 David Pépin. Third-party fonts, icons and sounds remain under their own licences (above).
