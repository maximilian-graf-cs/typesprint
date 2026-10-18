# TypeSprint

A multiplayer typing race game, written in TypeScript (hence the name).

**Status:** Work in progress. I'm building this as a learning project, so expect things to change a lot.

## What is it?

When the light turns green, you get a quote from a category of your choice and your car starts moving with your correct input. The faster you type, the faster it drives. Finish the quote first to win the race, but don't miss a beat or your opponents might end up winning.

## Planned features

- Race other players in real time (PvP)
- Race against bots with different difficulty levels (PvE)
- Quotes from movies, books, shows and more. Pick a category or search for a specific movie
- Two typing modes:
    - **Strict:** make a typo and you have to delete it and retype before you can continue
    - **Flow:** wrong keys are ignored and the race continues once you hit the right one
- WPM and accuracy after every race
- Leaderboards

## Tech stack

- **Bun** as runtime and test runner
- **Hono** for the API
- **PostgreSQL** with **Drizzle ORM**
- **Zod** for validation
- **Vue** for the frontend
- **WebSockets** for multiplayer

## Getting started

There isn't much to run yet, but here's how:

```bash
bun install
bun run index.ts
```

## Screenshots

Coming as soon as there's something to look at.

## Why I'm building this

I wanted a project where I actually understand every line I write, so I'm building it step by step and learning the stack along the way.