# Python-War-Card-Game
card game using OOP
Two players are playing a card game in which each of them has at most 26 cards. Players do not 
look at their cards but keep them in a packet face down. The objective of the game is to win all 
the cards initially owned by two players. Both players play by turning their top cards face up and 
putting them on the table. Whoever has the higher card takes both cards and adds them (face 
down) to the bottom of their packet. Cards rank as usual from high to low: A, K, Q, J, T, 9, 8, 7,
6, 5, 4, 3, 2. Suits are ignored. (implemented by isLargerThan(…)). Both players then turn up 
their next card and repeat. The game continues until one player wins by taking all the cards.
During a turn, if both players turn over cards of equal rank, the following process is used to 
decide a winner. The face-up cards stay on the table. Both players play the next card of their pile 
face down. Then, both players draw and turn over the next card of their deck face up. Whoever 
has the highest of those two face-up cards wins the war and adds all six cards to the bottom of his 
or her packet. The order of adding the six cards to the winner’s packet is based on the two initial 
cards on the table, the winner’s last card, and finally the loser’s last card. If the new face up cards 
are equal as well, the play continues: each player puts another card face down, then puts one card
face up afterward. The order is the first player’s card followed by the second player’s card. The 
process goes on like this as long as the opposing face up cards continue to be equal in rank. As 
soon as they are different, the player with the highest card from the last draw wins all the cards 
on the table. If someone runs out of cards in the middle of the process, the other player 
automatically wins. (implemented by solve(…) method)
The cards are added to the back of the winner’s hand in the exact order they were dealt, 
specifically player 1’s first card, player 2’s first card, player 1’s second card, etc. Your job is to 
write a program to simulate this game, report the number of moves, and print out each move via 
our provided methods/class.
