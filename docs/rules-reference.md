# Rules Reference

Back to index: [`README.md`](../README.md)

## Turn Flow

1. Start turn.
2. If in Dungeon, resolve Dungeon rule first.
3. Roll and move.
4. Resolve landed tile effect (buy, tribute, tax, card, or corner effect).
5. End turn.

## Buying and Tribute

- Buyable tiles: Properties, Minecart Depots, Utilities.
- Purchase currency: `Claim Tokens (CT)`.
- If another player owns the tile you land on, pay tribute immediately.
- Tribute values are defined in [`economy-values.md`](economy-values.md).

## Property Upgrades

- Same for all properties: `2 Outposts -> 1 Stronghold`.
- Build cost per step: `(Property CT cost)` on that tile.
- Tribute multipliers are defined in [`economy-values.md`](economy-values.md).

## Adventure Cards

- Draw and resolve immediately.
- Exception: keep-style cards are retained until used (currently `Get Out of Dungeon Free`).
- Full card list: [`adventure-cards.md`](adventure-cards.md).

## Dungeon Rules

- Landing on `Dungeon / Dungeon Visit` as normal movement is visit-only.
- `Sent to Dungeon`, `Dungeon Patrol`, or `Dungeon Warrant` sends player to Dungeon.
- Leave Dungeon by paying Dungeon fine or using `Get Out of Dungeon Free`.

## Bankruptcy and Winning

- If a player cannot pay what they owe, they must liquidate assets as your table rules allow.
- If still unable to pay, they are bankrupt and removed from the game.
- Last remaining non-bankrupt player wins.

