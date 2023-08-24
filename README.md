# tictactoe

This is a basic game of tictactoe where the goal is to get three in a row. 

# Structure
a 3x3 grid is created with each cell having a numbered value.

An onclick function runs so that the value of the string that indicates the turn (x or o) is passed into the cell's value.

Conditional statements run so that if a click was done by one player it swaps to the other player. 

On every click a for loop loops through the board and checks to see if the values that would constitute a win condition are the same. 

If they are, text appears saying that that player wins. 

# Learnings
getting the for loop to execute properly was the biggest issue i had as it checked to see who was the last click when any 3 cells in a row/column/diagonal were filled in instead of checking to see if they were the same before declaring a winner. 

This was just a simple case of performing the check function outside of the for loop. 
