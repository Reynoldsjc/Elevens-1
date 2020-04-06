1. You need a deck of cards, a place for 9 cards, and a discard pile.
2. You need to shuffle the deck, deal the appropriate amount of cards, figure out which ones the user wants to match and confirm if they can be, then remove them, then deal the cards again, and be able to determine when the game is over or when no match is possible.
3. Yes
4. a) at the end of the constructor b) anotherPlayIsPossible() isLegal() c) 0, 1, 3, 6, 7                 d) for (int I : cIndexes) { System.out.println(board.cards[I].toString()); }                 e) anotherPlayIsPossible() because you cannot select a null card for isLegal() but anotherPlayIsPossible() needs to separate the nulls before beginning.

