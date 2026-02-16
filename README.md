# 🧭 Pokedex CLI

A terminal-based Pokémon application built with Node.js and TypeScript, powered by the PokeAPI. It allows users to explore locations, catch and inspect Pokémon, and manage a personal Pokedex with an in-memory caching system for better performance. Built as part of the Boot.dev Backend Roadmap.


---
## 🚀 Features

- Browse location areas (`map`, `mapb`)
- Explore areas to discover Pokémon
- Catch Pokémon with probability-based mechanics
- Inspect detailed Pokémon stats (height, weight, stats, types)
- Maintain a personal Pokedex
- Custom caching system to reduce repeated API calls
- Unit tested using Vitest

---

## 🛠 Tech Stack

- Node.js  
- TypeScript  
- Vitest  
- PokeAPI  

---
## 📌 Example Usage

```txt
$ npm run dev

Pokedex > map
canalave-city-area
eterna-city-area
pastoria-city-area
...

Pokedex > explore pastoria-city-area
Exploring pastoria-city-area...
Found Pokemon:
 - tentacool
 - tentacruel
 - magikarp
 - gyarados
 ...

Pokedex > catch pidgey
Throwing a Pokeball at pidgey...
pidgey was caught!

Pokedex > catch caterpie
Throwing a Pokeball at caterpie...
caterpie escaped!

Pokedex > catch caterpie
Throwing a Pokeball at caterpie...
caterpie was caught!

Pokedex > pokedex
Your Pokedex:
 - pidgey
 - caterpie

Pokedex > inspect pidgey
Name: pidgey
Height: 3
Weight: 18
Stats:
  -hp: 40
  -attack: 45
  -defense: 40
  -special-attack: 35
  -special-defense: 35
  -speed: 56
Types:
  - normal
  - flying

Pokedex > exit
Closing the Pokedex... Goodbye!
```
---
## ▶ Run the Project

```bash
npm install
npm run dev
```
----
[![Boot.dev Backend Certificate](https://img.shields.io/badge/Boot.dev-Backend%20Certified-blue)](https://www.boot.dev/certificates/24b63348-4eea-4d5d-a1e2-6374f16fc9b0)
