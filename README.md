# KitsuneAugerReach

🦊 **Part of the [Kitsune Systems Collection](https://github.com/Kitsune-Den)** ~
[Kitsune Server Side Starter Kit](https://github.com/Kitsune-Den/KitsuneServerSideStarterKit) ·
[KitsuneZombieReach](https://github.com/Kitsune-Den/KitsuneZombieReach) ·
[KitsuneStacks](https://github.com/Kitsune-Den/KitsuneStacks)

**Gives the auger in 7 Days to Die a little more reach.**

The auger is the best digging tool in the game, and you still end up shuffling forward every few blocks because it barely reaches past the end of its own drill bit. This mod adds about a meter. You dig further into a wall or down a shaft before you have to step in, and you can hit something without being quite so close to it.

It's a small nudge, not a laser. Nothing else about the auger changes: damage, speed, fuel and durability are all vanilla.

## What it changes

Only `meleeToolPickT3Auger`. Values are in meters.

| | Vanilla | Mod |
|---|---:|---:|
| `BlockRange` (digging blocks) | 3.5 | **4.5** |
| `MaxRange` (hitting zombies and animals) | 2.35 | **3** |

## Requirements

- 7 Days to Die V3.x (checked against V3.3.0 b18 `items.xml`)
- Server-side only. The server sends its item config to players, so clients don't install anything.
- EAC-safe. Pure XML, no DLL.

## Installation

1. Drop the `KitsuneAugerReach` folder from the release zip into your server's `Mods/` folder (or your own, for single player).
2. Restart the server.

It's also in the [Kitsune Server Side Starter Kit](https://github.com/Kitsune-Den/KitsuneServerSideStarterKit).

## Tuning it

Want more, or less? Edit the two numbers in `KitsuneAugerReach/Config/items.xml`. If you only want longer digging, set `MaxRange` back to `2.35`.

Made by AdaInTheLab.

## License

[CC BY-NC-SA 4.0](LICENSE), with an extra permission for servers that make money: see [NOTICE.md](NOTICE.md). In short: play it, change it and share it, with credit, not for sale, and with changed versions under the same license.
