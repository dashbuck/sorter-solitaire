# Sorter Solitaire

Feel the pure satisfaction of having things sorted into the correct groups and ordered in the correct sequence.

Kind of more of a toy than a game, since there's no way to lose. Whatever grouping and order makes sense to you is the correct one.

## MVP Features

- Display decks
- Select deck
- Display card
- Take user input
- Put card in correct deck

## Notes
This is a game that's more of a toy. The goal is visceral satisfaction in having things sorted and organized and clean. The feel of the action of sorting is very important. On phones it should be left/right swipes. On a controller, two opposing buttons. Desktop arrow keys probably. In all cases it should support reassignment in case someone wants to use A and L keys for example.

#### Game Loop
1. View full card deck at once (design should have corner references like trad poker deck)
2. Label swipe directions. All card elements available - eg color, suit, number. Choosing not to assign a direction will be "Everything else" by default. Probably a tap to select one or more options, maybe tapping the edges of blocks to set swipe direction.
3. Start sort. No timer. Swipe left and right. This is meant as a relaxing, soothing, calm, meditative thing. Subtle noises for items that match the label or don't? Colors? 
4. Sort ends. Play subtle success music, maybe a lil animation. 
5. Player can then can select and view one of the decks they've created.
6. While viewing, they can choose to take one of three actions: sort, reorder, complete.
	7. Sort: Start loop from 2.
	8. Reorder: Reorder the deck stack by selecting and swapping any two individual items. This probably needs to be its own view, with uncompressed layout that allows for scrolling. When ready, return to the deck view and start loop from 6.
	9. Complete: The player is satisfied with the sort and order of the deck. A more complicated animation allowing the player to admire their accomplishment will play, and then the deck will be added to the bookshelf. When ready, return to the deck view and start loop from 6.

Bookshelf: Players will fill the bookshelf over time and can reorganize the book-decks in any order they prefer. They can trigger a full collection or individual book-deck animation at any time from the bookshelf view. Each shelf will be its own deck. 

Maybe add an idle mechanic that allows you to accrue points to unlock new decks? Or just unlock one deck at a time? Get one deck done to begin with, sheesh!

#### MVP
- Display decks
- Select deck
- Display card
- Take user input
- Put card in correct deck

Everything else described is gravy tbh.