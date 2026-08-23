# Inn

**Pet Tavern Keep** — Run a cozy pub for traveling virtual pets — visitors from Visitation sit and sip.

Part of the [ComputerPets](https://github.com/RicheyWorks/computerpets) universe. Map: [computerpets-ecosystem](https://github.com/RicheyWorks/computerpets-ecosystem).

> Status: **design scaffold**. Gameplay contract is frozen. Engine choice is the one in the brief. Implementation comes next.

## Loop

Hearth is the village. Inn is the business on the square. Patrons are other players' pets (guests, not stolen). Tips in treats. A sleeping Rui is a bad barkeep.

## Genre & engine

- Genre: **Business sim**
- Engine: **Unity**
- Stack: Unity 6 · C# · tavern loop · visiting pets as patrons · meals from Kettle
- Default surface: `Unity editor`

## How you play

1. Set menu + hours.
2. Seat guest pets. Serve biome-legal drinks.
3. Reviews affect tomorrow's traffic.
4. Close up → overlay pets clock out.

## Talks to

- computerpets-visitation
- computerpets-hearth
- computerpets-kettle
- computerpets-ledger
- computerpets-discord (nightly last-call)

## Failure doctrine

Guest pet recalled mid-sip → leave a tip and vanish. Ledger down → run on IOU, settle later. No gambling tables (Ballot is elsewhere).

Canon rules that never yield:

- 210 living kinds. No illegal hybrids.
- Overlay pets can get tired, sick, or hide. Tokens are not burned by a minigame.
- Desktop walk stays the main quest. Closing Inn must leave Rui walking.

## Layout

```
computerpets-inn/
  README.md
  LICENSE
  docs/DESIGN.md
  src/                implementation lands here
```

## Run (Windows)

```powershell
Unity Hub > Inn/; play mode.
```

Meet Rui first via the [flagship start-here](https://github.com/RicheyWorks/computerpets/blob/main/docs/START-HERE.md). This game is optional.

## License

MIT. See [LICENSE](LICENSE).

---

*Two hundred ten living kinds. Keep them so a line does not go quiet.*
