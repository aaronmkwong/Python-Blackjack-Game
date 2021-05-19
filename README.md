# Python-Blackjack-Game

The program generates a 1 player basic blackjack game without double-down and card splits. 

Classes include Deck, Hand and Chips. Functions include "continue playing", "change cash for chips", "wager" and "player hit or stand". I think the code could have been reduced with the use of an "outcome" function in conjunction with the classes since the same three lines are repeated. Incorrect player inputs are handled within the functions.

The dealer introduces her/him/themself from a randomized tuple of names and asks the player for their name and to choose an amount of cash to change to chips. 

A game loop begins, the deck is shuffled and the dealer prompts the player to make a wager. Two cards are dealt to the dealer and player who show one and both respectively. If the player has 21, then a push outcome is assessed or an automatic stand ensues and a dealer loop of hits is entered until a push or bust outcome is reached.

Otherwise, a hit-stand loop begins and the dealer prompts the player to hit or stand. If the player hits, then a push outcome is assessed, an automatic stand ensues and a dealer loop of hits is entered until a push or bust outcome is reached, or a player bust outcome is assessed. If the hit is insufficient to determine an outcome, then the hit-stand loop continues. If the player stands, then a player loss or win outcome is assessed based on existing dealer and player cards; else, a dealer loop of hitting ensues until a win, loss, push or bust outcome arises.

After a hand outcome is determined the dealer prompts the player whether to play again. If so, then the game loop continues. If not the dealer, says goodbye to the player and says their final chip total.
