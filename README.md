# Galaxy Genome Wiki

An unofficial guide to
[Galaxy Genome](https://play.google.com/store/apps/details?id=com.skvgames.GalaxyGenome),
the space sim by SKV Games: what a scan is worth, what an ore sells for, what a
job pays at each standing, and what the game never tells you.

**[Read it](https://galaxy-genome.github.io/wiki/)** ·
**[On Fandom](https://galaxy-genome.fandom.com/)**

Both are the same articles, published from the same source. Galaxy Genome and
all of its data belong to SKV Games.

## What is here

- `docs/index.html` — every article, rendered from wikitext in the browser. This
  is what GitHub Pages serves.
- `Wiki-navigation.txt` — the Fandom navigation menu, to paste into
  `MediaWiki:Wiki-navigation`.

Neither is written by hand. Both are built by `port/build_wiki.py` in the
[tools repository](https://github.com/galaxy-genome/map), which reads the game's
own tables and the swept galaxy, and checks every link it writes against the
map's data before it publishes.

## Licence

The articles are CC BY-SA 4.0, matching Fandom, so text can move between the two
freely. The game's data belongs to SKV Games and is used with the developer's
permission.
