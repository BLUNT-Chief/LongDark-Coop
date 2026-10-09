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

- **Host:** on the main menu choose **CO-OP → HOST A GAME**, then start a new survival game or load one as usual.
  It's open to your friends as soon as it loads. In game, press **Esc → CO-OP → INVITE FRIENDS**. (You can also
  host a game you're already playing: **Esc → CO-OP → HOST THIS GAME**.)
- **Join:** on the main menu choose **CO-OP**; friends who are hosting are listed there. You can also accept a
  Steam invite, or right-click the host in your Steam friends list and choose **Join game**. Your game loads the
  host's world and puts you next to them.
- **Esc → CO-OP** shows who's playing and where. The host can kick or ban players, choose who can join, and back
  up the world (it's also backed up automatically every 30 minutes).
- **Host console:** the host can press **~** (the key left of 1) for the game's own console commands, such as
  `set_time 12`, `set_weather` or `spawn_wolf`. Type `help` or `search <word>` to find commands, and Esc closes it.

The host's world is the save. Your character (inventory, condition, skills) is kept per player, so it's waiting for
you the next time you join that host.

## Options

**CO-OP → WORLD OPTIONS** (the host's choices apply to everyone):

- **Animals:** fewer, normal, more per player (a quarter more for each extra player), or x1.5, x2 or x3.
- **Respawns:** how quickly hunted-out areas fill up again.
- **Downed for, reviving takes, revived with:** how downed and revive work, or turn downed off.
- **Shared map, backups, players:** whether exploration is shared, how often the world is backed up, and how many
  can join.

**CO-OP → MY OPTIONS:** name tags, edge markers, marks (middle mouse) and teammates on the map, each on or off.

**CHARACTER:** whose face your friends see on you (Astrid, Jeremiah, Methuselah, Hobbs or Mathis, from the
WINTERMUTE story mode). Your body wears the clothes you actually have on. Faces need WINTERMUTE installed; it comes
with The Long Dark, and you can install it from the game's DLC list in Steam.

## What's shared

- Time of day, weather and wind.
- Doors, containers, loose items, fires, broken-down furniture, harvested plants and carcasses.
- Snow shelters, rope climbs, and lanterns, torches, flares and snares left on the ground.
- Rock caches (built, renamed, dismantled) and what's inside them.
- Cooking: a pot or skillet on a fire, what's cooking in it, and taking it out.
- Decorations (nearly anything you can pick up and move around a base) where you put them.
- Spray paint marks and ice fishing holes.
- You hear teammates: their footsteps and their shots, where they are. They leave footprints in the snow, and
  their breath shows in the cold.
- Wildlife: each animal runs on the nearest player's game, so wolves stalk and attack whoever they're after.
  Shooting or hitting an animal works from any player's game.
- Sleeping and passing time only start once every player chooses to.

## Finding each other

- Teammates show on the map in their own color, with their names. Someone indoors shows where they went in.
- Name tags show how far away each teammate is. A teammate off screen gets a marker at the edge of your screen
  pointing their way.
- **Middle mouse** marks the spot you're looking at for everyone, for 20 seconds.
- The map is shared: whatever anyone charts with charcoal or discovers shows up on everyone's map.
- **Give an item:** stand next to a teammate (within 3 m), open your backpack, pick the item and choose
  **GIVE TO <NAME>**. It goes straight into their backpack. Hold shift to give the whole stack.

## Dying

When you would die and a teammate is in the same area, you go down instead. A teammate who stands next to you
for 4 seconds revives you. If nobody does within 60 seconds, the game's own respawn ("Cheat Death") takes over,
and the gear you lose waits in a recovery camp where you fell. In co-op you never run out of lives, and the shared
save is never deleted.

Coming next: carrying a downed teammate to shelter, and more ways to play together.

## Uninstall

Run **LongDarkCoopSetup.exe** again and click **Uninstall**. Your saves are not touched. MelonLoader is removed only
if this setup installed it.

## Reporting a bug

Send what happened, plus this file from the game folder (Steam: right-click The Long Dark, then
**Manage → Browse local files**): `MelonLoader\Latest.log`.

---

The Long Dark belongs to Hinterland Studio Inc. This is a free, unofficial fan modification and is not affiliated
with or endorsed by Hinterland.
