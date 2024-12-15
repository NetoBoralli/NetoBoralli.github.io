---
title: "Astrodex"
description: "Pokedex built with Astro, Node.JS and PokeAPI."
date: "Dec 11 2024"
demoURL: "https://astrodex-netoboralli.netlify.app"
repoURL: "https://github.com/NetoBoralli/astrodex"
---

![Astrodex](/astrodex.png)

Astrodex is a static pokedex built with Astro.JS and PokeAPI. The only peculiarity about this project is that, because of limitations of PokeAPI, all pokemon data was created with a node.JS script and saved in the project as Markdown files. In the end this was a positive, because now the whole project can be static and don't require any external API calls to work.

One evolution of this project will be the capacity of generating the Markdown files during the build process. This wasn't a worry for this first version because the rate where we get new pokemon data is not that big, so the project can live some time with a more "manual" process instead of a build integration.

## 📋 Features

- ✅ Listing of All 1025 pokemon
- ✅ Responsive
- ⬜️ Pokemon MD generated at build time
- ⬜️ Specific view of each pokemon
- ⬜️ Search pokemons in the listing
- ⬜️ Checklist of collected pokemon
