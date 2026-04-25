# Catan

## Complete Description of the Catan Board Game

Catan is a strategy board game for 3–4 players (2 players in some variants) where each player leads a small colony on an island made of hexagonal terrain tiles. The objective is to be the first player to reach **10 victory points**.

### Core idea
Players collect and spend resources to build roads, settlements, and cities. Resource production depends on dice rolls and where you place settlements.

### Components (base game)
- 19 terrain hexes:
  - 3 brick hills
  - 4 lumber forests
  - 4 wool pastures
  - 4 grain fields
  - 3 ore mountains
  - 1 desert
- Number tokens (2–12, excluding 7 on tiles)
- Robber piece (starts on the desert)
- Player pieces (roads, settlements, cities)
- Development cards
- Resource cards

### Setup
1. Build the island board from 19 hexes and place number tokens on non-desert hexes.
2. Place robber on the desert.
3. Each player places one settlement + one connected road in turn order.
4. Then players place a second settlement + connected road in reverse order.
5. After second placement, each player collects 1 resource from each adjacent producing hex.

### Turn structure
1. **Roll dice (2d6)**
   - Terrain hexes with the rolled number produce resources.
   - Players with settlements adjacent to those hexes gain 1 card of that resource.
   - Cities gain 2 cards.
2. **If 7 is rolled**
   - Players with more than 7 cards discard half (rounded down).
   - Active player moves robber to any hex.
   - That player steals 1 random resource from a player with a building adjacent to that hex.
3. **Trade**
   - With other players (any negotiated trade).
   - With bank (typically 4:1, better rates with ports).
4. **Build / Buy / Play cards**
   - Build road: 1 brick + 1 lumber
   - Build settlement: 1 brick + 1 lumber + 1 wool + 1 grain
   - Build city: 2 grain + 3 ore (upgrades a settlement)
   - Buy development card: 1 wool + 1 grain + 1 ore
5. **End turn**

### Development cards (base)
- **Knight**: Move robber, possibly steal.
- **Road Building**: Place 2 free roads.
- **Year of Plenty**: Take any 2 resources from bank.
- **Monopoly**: Claim all cards of one resource type from opponents.
- **Victory Point**: Hidden point card.

### Scoring and win condition
Victory points come from:
- Settlement: 1 VP
- City: 2 VP
- Largest Army: 2 VP (first to 3+ played knights and most)
- Longest Road: 2 VP (road length 5+ and longest)
- Victory Point development cards: 1 VP each

First player to **10 VP** wins.

## Playable Single-File Web Version
Open `index.html` in a browser. It includes a local multiplayer adaptation with:
- Full hex board and number token generation
- Robber movement and stealing
- Building roads, settlements, and cities
- Development cards
- Longest Road and Largest Army scoring
- Bank trade and simple player trade
- Automatic win detection
