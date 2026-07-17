# MossDungeons

MossDungeons is a complete dungeon engine built for running repeatable, configurable adventures on a live Paper server. It handles the world work, encounter flow and player-facing progression so a dungeon can feel designed rather than stitched together from commands.

## Core systems

- Template-based dungeon generation using WorldEdit or FastAsyncWorldEdit
- Multi-stage dungeon runs with checkpoints, difficulty settings and runtime events
- Configurable actions, conditions, effects, rewards and custom chest behavior
- In-game editors for dungeon regions, generation settings and gameplay options
- Leaderboards, holograms and persistent player data
- SQLite and MySQL storage options
- Party and access-control hooks for several popular party plugins

The integration layer is deliberately broad. Dungeons can respect WorldGuard, Towny, GriefPrevention, GriefDefender and KingdomsX claims, use Fabled classes, display through multiple hologram plugins, and work with ItemsAdder or MMOItems content.

My focus with this project is flexibility without making every new dungeon a programming task. Server staff should be able to assemble the experience from templates, menus and configuration while the engine takes care of lifecycle and cleanup.

## Source availability

MossDungeons is closed-source and built for private production use. This repository shares the project's design and capabilities without exposing its code or dungeon content.
