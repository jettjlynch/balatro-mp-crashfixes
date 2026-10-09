# Balatro Multiplayer Crash Fixes

A tiny drop-in mod that fixes three crashes when playing **Balatro Multiplayer** together with **Cryptid** and **Amulet** on the latest Steamodded.

It doesn't change any of your other mods' files. It just patches them as the game loads, so it works on Mac and Windows.

## What it fixes

| Crash | When it happens | Mods involved |
|---|---|---|
| `attempt to index field 'last_choices' (a nil value)` | Opening the deck picker in a lobby on a fresh profile | Cryptid |
| `attempt to index field 'effect' (a nil value)` | Clicking the **Cocktail** deck in a lobby | Steamodded + Multiplayer |
| `attempt to call global 'is_big' (a nil value)` | Connection drops and the game tries to reconnect | Amulet + Multiplayer |

## Tested with

- Lovely 0.10.0
- Steamodded 26.1002.0
- Multiplayer 0.5.5
- Cryptid 0.5.17c
- Amulet 3.6.1

## How to install

1. Download **MPCrashFixes.zip** from the [Releases page](../../releases/latest).
2. Unzip it. You'll get a folder called `MPCrashFixes`.
3. Put the `MPCrashFixes` folder in your Balatro **Mods** folder:
   - **Windows:** `%AppData%\Balatro\Mods`
   - **Mac:** `~/Library/Application Support/Balatro/Mods`
4. Start Balatro (with Lovely) as normal.

To remove it, delete the `MPCrashFixes` folder.

Both players should install it, so your mod lists match.
