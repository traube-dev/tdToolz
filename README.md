---
name: tdToolz
tagline: Shared framework and settings menu (F2) used by all traube.dev mods - plus its own chat, permissions, security, and host tools
thumbnail: thumbnail.png
icon: icon.svg
---

tdToolz is the foundation every other traube.dev mod is built on - it gives every mod a shared, consistent F2 settings menu instead of each one bringing its own separate UI, and it comes with its own set of host and multiplayer tools on top of that.

## Features
- Shared F2 settings menu - every installed traube.dev mod gets its own tab in the same window automatically
- In-game Package Manager - browse, install, update, and uninstall traube.dev mods without leaving the game, each with its own description, changelog, and icon/thumbnail pulled straight from its GitHub repo
- LuckPerms-style permission system - create groups and nodes, assign players, host-only to edit
- TZSecurity - blocks a long list of forged-RPC exploits (forced respawns, input hijacking, teleport forgery, and more) out of the box, plus a threat monitor that can notify you or automatically kick/ban repeat offenders, with a host-side whitelist for trusted players
- Persistent Steam ID ban list - survives restarts, auto-kicks a banned player the moment they try to rejoin
- Always-on chat log over Steam's native lobby chat, with clickable links, per-player muting, and a toggle to hide everyone else's messages
- Dev Mode - host-only toggle that locks the weather clear and the time at noon, handy for testing or showcasing something without the game randomly throwing rain or night at you

## Requirements
- Wobbly Life (via Steam)
- BepInEx 5.x

## Installation
See [traube.dev/docs](https://traube.dev/docs.html) for the general BepInEx + mod install walkthrough. No manual `BepInEx.cfg` editing needed - tdToolz protects itself (and every mod built on it) from the game's scene-cleanup automatically on every launch.
