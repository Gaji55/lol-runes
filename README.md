# LoL Runes

A small Windows app for League of Legends. In champ select it shows the op.gg
build for your champion and lane (runes, summoner spells, skill order, items,
counters) and imports runes, spells and an item set into the client with one
click.

## Download

**[LoL-Runes-Setup.exe](https://github.com/Gaji55/lol-runes/releases/latest/download/LoL-Runes-Setup.exe)**
(always the newest version)

Run it. Windows may show a blue "Windows protected your PC" box because the
installer is not code-signed: click **More info**, then **Run anyway**. It
installs for your user only, no admin rights needed.

## Using it

- It sits in the tray (teal diamond in a gold ring) and opens by itself in
  champ select, then closes when the game loads. The Start menu entry opens it
  any time to look up a champion.
- **Import** writes the ticked parts: a rune page called `op.gg <Champion>
  <Lane>` (your other pages are left alone; the first import replaces your
  oldest page if all slots are full), the summoner spells (Flash stays on your
  key), and an item set.
- The rank dropdown picks whose games the builds come from. *My rank+* (the
  default) uses your rank and above.
- Tray menu: keep the window open during games, start with Windows, quit.

## Updates

It updates itself. New versions are downloaded from this page and installed
quietly while League is closed, in the lobby or after a game, never during
champ select or a game.

## What it talks to

- **Your League client**, through its local API on your own PC, the same way
  Porofessor or Blitz do. Riot allows this for champ select tools.
- **op.gg** for the builds, **Riot's Data Dragon** for names and icons, and
  **GitHub** to check for updates. Nothing about you or your account is sent
  anywhere.

## Uninstall

Windows Settings, Apps, **LoL Runes**, Uninstall. It removes everything,
including its cache.

---

LoL Runes isn't endorsed by Riot Games and doesn't reflect the views or
opinions of Riot Games or anyone officially involved in producing or managing
Riot Games properties. Riot Games, and all associated properties are trademarks
or registered trademarks of Riot Games, Inc. Not affiliated with OP.GG.
