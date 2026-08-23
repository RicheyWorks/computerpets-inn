# Inn design

Implement against this file, not folklore.

## Identity

- Product: **Inn**
- Repo: `computerpets-inn`
- Idea: Pet Tavern Keep
- Genre: Business sim
- Engine: Unity
- Surface: `Unity editor`

## Loop

Hearth is the village. Inn is the business on the square. Patrons are other players' pets (guests, not stolen). Tips in treats. A sleeping Rui is a bad barkeep.

## Play beats

- Set menu + hours.
- Seat guest pets. Serve biome-legal drinks.
- Reviews affect tomorrow's traffic.
- Close up → overlay pets clock out.

## Neighbors

- computerpets-visitation
- computerpets-hearth
- computerpets-kettle
- computerpets-ledger
- computerpets-discord (nightly last-call)

## Failure doctrine

Guest pet recalled mid-sip → leave a tip and vanish. Ledger down → run on IOU, settle later. No gambling tables (Ballot is elsewhere).

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
