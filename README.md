# azerothcore-custom-modules - GvG Server

This repository contains a set of custom modules for a **Guild vs Guild (GvG)** server based on **AzerothCore 3.3.5a**.  
Each module is independent and designed to be integrated through the `modules/` folder of AzerothCore.

---

## Modules Overview

| Module              | Purpose |
| ------------------- | --------------------------------------------------------- |
| `mod-gvg-core`        | Core GvG / PvP: manages war states, PvP hooks, internal API, global guild tracking |
| `mod-zone-control`    | Zone capture via banners, manages ownership and timers |
| `mod-zone-resources`  | Automatic resource generation (gold, wood, etc.) for guilds controlling zones |
| `mod-gvg-npc-spawn`   | Automatic NPC spawns when a zone is captured |
| `mod-gvg-build`       | Temporary construction via items (GOBs, barricades) |
| `mod-gvg-mounts`      | Custom mounts with modified speed for guild members |
| `mod-gvg-gearshop`    | Buy gear packs (S5 → S8) using guild resources |
| `mod-gvg-knockout`    | 1 HP KO system: stunned, execution, or prison |
| `mod-gvg-prison`      | Prison system, ransom, rewards for capturing guilds |
| `mod-gvg-lootdrop`    | Lootable chest on player death (gear, gold, resources) |
| `mod-gvg-bounty`      | Bounty system for targeted players (highest gear/stats) |
| `mod-gvg-alliance`    | Temporary alliances between guilds with resource sharing |
| `mod-gvg-mercenaries` | Mercenary services: pay another guild for defense/attack |
| `mod-gvg-limitations` | Gameplay limits: max 30 members per guild, max 5 per group |
| `mod-gvg-ui`          | Custom UI, gossip menus, HUD, and GvG displays |
| `mod-gvg-skin`        | Skin pack to be obtained as a reward |

---
