# Battle 21 Card Game

A strategic card game where players use a standard deck plus jokers to battle until one player reaches 21 damage or runs out of cards.

## Game Overview

Battle 21 is a browser-based card game that combines elements of traditional card games with strategic tabletop gameplay. Players take turns playing cards from their hand to attack, defend, or use special abilities while managing their resources and positioning.

## How to Play

### Setup
1. The game automatically deals a deck of 52 cards plus 2 jokers between two players (26 cards each)
2. Each player starts with 3 cards in hand and 0 damage points
3. The human player goes first

### Card Types
Cards have different functions based on their suit:

- **Hearts (Red)**: Attack cards that deal damage equal to their value
- **Clubs (Black)**: Defense cards that block incoming damage
- **Diamonds (Red)**: Purchase cards that let you take cards from your opponent's field
- **Spades (Black)**: Recovery cards that let you retrieve cards from your graveyard
- **Special Cards**:
  - **Aces**: Swap all cards on both players' fields
  - **Jokers**: Force your opponent to discard their entire hand

### Game Mechanics

#### On Your Turn
You may:
1. Draw a card (by clicking your deck)
2. Play one damage card (Hearts) OR one defense card (Clubs)
3. Use one ability card (Diamonds, Spades, Aces, or Jokers) 
4. End your turn (or pass)

#### Card Interactions
- **Hearts (Attack)**: Deal damage directly to your opponent unless they have Clubs for defense
- **Clubs (Defense)**: Block incoming Heart attacks of equal or lower value
- **Diamonds (Purchase)**: Take a card from your opponent's field with value less than or equal to the diamond
- **Spades (Recovery)**: Return a card from your graveyard to your hand with value less than or equal to the spade
- **Aces**: Swap all cards on the field between players
- **Jokers**: Force your opponent to discard their entire hand

### Winning the Game
The game ends when:
1. A player accumulates 21 or more damage points (the other player wins)
2. A player runs out of cards in both their deck and hand (the other player wins)

## Controls
- Click your deck to draw a card
- Click a card in your hand to play it
- Click "End Turn" to end your turn
- Click "Pass" to pass your turn without playing

## Strategic Tips
- Keep defense cards (Clubs) on your field to protect against attacks
- Use Diamonds strategically to purchase valuable cards from your opponent
- Save Aces and Jokers for when they'll have maximum impact
- Pay attention to your opponent's field and plan your moves accordingly
- Remember that your hand has a maximum limit of 5 cards

## Advanced Features
The game includes additional strategic elements such as:
- Field positioning with different zones for attack, defense, and support
- Card synergies and formation bonuses 
- Energy/durability system for cards
- Resource management for using abilities

## Technical Notes
- The game runs entirely in the browser using HTML, CSS, and JavaScript
- No internet connection is required after the initial page load
- The AI opponent makes strategic decisions based on card values and field conditions