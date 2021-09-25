# MNORLD Card Game

## Game Starts

- Number cards are added
- Cards are shuffled
    - Players hands are delt
    - Off by one byte card is stored
- Special cards are added
- Cards are shuffled

- Game play starts

## Players Turn

 - Check for "error cards"
    - If found loses a turn
    - Redraw's a card
 - Check for "extra byte cards"
    - If found adds a card to the PLAYER'S DECK
    - Redraw's a card

 - Player/Computer chooses HAND CARD and CHALLENGE CARD
 - Challenge Hand card agains Deck Cards
 - Check for a match
    - if a match found set card as matched (turn over card)
 - Check if there is a winner
 - Check if we still have cards in the shuffle deck

 - Check for "overclock cards"
    - If found - Do Not Switch players turn (since they go twice)
    - If NOT FOUND switch to the other players turn 