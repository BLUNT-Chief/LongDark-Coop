# Long Dark Co-op

Online co-op for **The Long Dark** on Steam: up to 4 players in one survival world. You host with Steam lobbies
and invite friends; there are no IP addresses to type and no ports to forward.

> **Early test build.** Expect bugs. Back up your saves before playing
> (`%LOCALAPPDATA%\Hinterland\TheLongDark`).

## Install

1. Close The Long Dark.
2. Download **LongDarkCoopSetup.exe** from the [latest release](../../releases/latest) and run it.
   Windows may warn that the app is unrecognized: click **More info**, then **Run anyway**.
3. Check that the game folder it found is right, then click **Install / Update**.

Setup installs MelonLoader 0.7.3 (the mod loader), the mod, and a small updater. After that, the game updates the
mod by itself every time it starts, so you only run setup once.

Requires The Long Dark **2.55** on Steam (Windows).

## Play

- **Host:** load or start a survival game, press **Esc**, then click **Host this game** in the Long Dark Co-op
  panel and **Invite friends**.
- **Join:** accept the Steam invite, or right-click the host in your Steam friends list and choose **Join game**.
  Your game loads the host's world and puts you next to them.

The host's world is the save. Your character (inventory, condition, skills) is kept per player, so it's waiting for
you the next time you join that host.

## What's shared

- Time of day, weather and wind.
- Doors, containers, loose items, fires, broken-down furniture, harvested plants and carcasses.
- Wildlife: each animal runs on the nearest player's game, so wolves stalk and attack whoever they're after.
  Shooting or hitting an animal works from any player's game.
- Sleeping and passing time only start once every player chooses to.

## Finding each other

- Teammates show on the map in their own color, with their names. Someone indoors shows where they went in.
- Name tags show how far away each teammate is. A teammate off screen gets a marker at the edge of your screen
  pointing their way.
- **Middle mouse** marks the spot you're looking at for everyone, for 20 seconds.
- The map is shared: whatever anyone charts with charcoal or discovers shows up on everyone's map.
- To give someone an item, drop it near them; they can pick it up.
- The Long Dark Co-op panel in the pause menu (**Esc**) lists where everyone is.

## Dying

When you would die and a teammate is in the same area, you go down instead. A teammate who stands next to you
for 4 seconds revives you. If nobody does within 60 seconds, the game's own respawn ("Cheat Death") takes over,
and the gear you lose waits in a recovery camp where you fell. In co-op you never run out of lives, and the shared
save is never deleted.

Coming next: host tools (kick, save backups) and a real character model.

## Uninstall

Run **LongDarkCoopSetup.exe** again and click **Uninstall**. Your saves are not touched. MelonLoader is removed only
if this setup installed it.

## Reporting a bug

Send what happened, plus this file from the game folder (Steam: right-click The Long Dark, then
**Manage → Browse local files**): `MelonLoader\Latest.log`.

---

The Long Dark belongs to Hinterland Studio Inc. This is a free, unofficial fan modification and is not affiliated
with or endorsed by Hinterland.
