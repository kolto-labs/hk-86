# hk-86

A Discord bot that manages curated, self-assignable community roles, in an HK voice, with a small web panel.

## Scope

- Role bot: reads the live guild roles, applies hierarchy-safe adds and removes, reports blocked roles
- Web panel
- HK dialogue data

## Contracts

- Sign-in: client of the org-wide OpenID Connect service. No login code lives here.
- Discord plumbing: `kolto-bot-kit`.

## Status

Scaffold. Code is being migrated from `OpenKotOR/community-bots` with history, one draft pull request at a time. The licence has not been chosen yet, so no licence is granted until a `LICENSE` file lands.

Kolto Labs is an independent, non-commercial fan project, not affiliated with Lucasfilm, Disney, BioWare, Electronic Arts, Obsidian, Aspyr or Saber Interactive. This repository contains no game assets.
