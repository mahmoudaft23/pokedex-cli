# 🧭 Pokedex CLI

A terminal-based Pokémon application built with **Node.js** and **TypeScript**, powered by the **PokeAPI**.

This project allows users to explore Pokémon locations, catch Pokémon, inspect their stats, and maintain a personal Pokedex — with a custom in-memory caching system for improved performance.

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
