# stringdex

Pokémon GO search strings you can copy in one tap, a builder for making your own, and a plain English guide to every search term.

**Live site:** https://lachlanalston.github.io/stringdex/

## Features

* **Ready made strings.** Silver and Gold Bottle Cap upgrades, plus safe transfer strings for the last 7 days or all time. Search or tap a button, then copy.
* **Builder.** Tap chips to build your own string. Every tap adds an AND, and "+ or" adds options to a group, the same way GO reads searches. Includes custom CP ranges and share links.
* **Terms.** Every storage, friends list and Pokédex search term, explained and tappable to copy.
* **Works offline.** Add it to your home screen and it runs like an app.
* **Private.** No accounts, tracking or ads. Nothing leaves your phone.

## Using a string

1. Tap **Copy**.
2. Open your Pokémon storage in GO.
3. Paste into the search bar.

To keep a string in GO, tap See more in the search bar, then hold it under Recent to pin it to Favourites.

## A string stopped working?

Niantic sometimes renames search terms. Please [open an issue](../../issues) with the string name and what happened.

## Suggest a string

Open an issue with the string, what it finds, and confirmation you've tested it in game.

## Editing

Everything lives in `index.html`. There are no dependencies or build step.

| What | Where |
|---|---|
| Ready made strings | `PRESETS` (title, desc, keywords, string) |
| Quick buttons | `SUGGEST` |
| Transfer protections | `PROTECT` |
| Builder chips | `GROUPS` |
| Terms page | `TERMS` |

After any change, bump `VERSION` in `sw.js` so installed copies update.

## Deploying

Settings > Pages > Deploy from branch > `main` / root.

## Credits

Search term details cross checked against [GO Hub](https://db.pokemongohub.net/tools/search-strings) and [Serebii](https://serebii.net/pokemongo/pokemonsearch.shtml), then tested in game.

Fan made tool. Not affiliated with Niantic, Nintendo or The Pokémon Company. Pokémon and Pokémon GO are trademarks of their respective owners.
