# set-game
A card matching game in the terminal!

This was a coding assignment I received from one of the companies I applied to as a software developer intern.

**"**

**~RULES GIVEN~**

"Set" is a card game where a group of players try to identify a "set" of
cards from those placed face-up on a table.
Each card has an image on it with 4 orthogonal attributes:

 - Color (red, green, or purple)
 - Shape (diamond, squiggle, or oval)
 - Shading (solid, empty, or striped)
 - Number (one, two, or three)

Three cards are a part of a set if, for each property, the values are
all the same or all different.

*For example:*

- The cards "two red solid squiggles", "one green solid diamond",
  "three purple solid ovals" would make up a set. (number, shape, and color
  are different, shading is the same)

- The cards "two red solid squiggles", "one green solid squiggles",
  "three purple solid ovals" would not make up a set, because shape is the
   same on two cards, but different on the third.

- A game of Set starts by dealing 12 cards, face-up. When a player sees
   three cards that make up a set, they yell "Set!" and grab the cards.
   New cards are dealt from the deck to replace them.

- If no player can find a set, three more cards are dealt
  (to make 15, then 18, then 21...)
- The game is over when there are no cards left in the deck, and no
  sets left on the table. The player with the most sets wins.

**"**
