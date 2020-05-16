
NOTE : The files for both programs are .txt extension since my PC does not have Python installed


# TASK : PYTHON PROGRAM TO IMPLEMENT 2048 GAME. 

INTERPRETER USED : onlinegdb.com

# GAMEPLAY DESCRIPTION
	The game starts with the user entering the winning number(default value 5) , size of the board(default value 2048). Once entered, a game board is displayed with a 2 on the board. The user has the option to move up('W'), move down('S'), move left('A') or move right('D') given that their move causes a change in the board orientation. If not, a message is displayed stating the same and the user is expected to play their move again. While moving in any direction, changes can be made by the following ways-  1)All non zero numbers are shifted to the farthest possible position in the direction of motion, in order of their position. Their original postions are replaced with zeroes. 2) If 2 contiguous elements in direction of motion have the same value, the farther element in the direction of motion, gets a value double of its original, and the other value becomes zero. Step 1) is repeated after 2) once more to ensure all non-zero values are as shifted away as possible in direction of motion. For every succcessful move, a 2 is randomly placed at one position on the board which originally had a zero. The user is then asked to enter a direction of motion again following the same rules for play with a 2 being added after each successful move.

# WINNING A GAME
	A user wins a game when they manage to have atleast one element on the board which is equal to the winning number. If the user enters a value which is not a exponent of 2, the game would be won when the user manages to play thorugh to have a value on the board greater than the winning number.

# LOSING THE GAME
	A user loses the game when they have no possible directions left for movement, that is, the board is full with no possible moves causing a change in the game board.

# ACTIONS
	W : Shift,merge elements up.
	S : Shift,merge elements down.
	A : Shift,merge elements left.
	D : Shift,merge elements right.	
    
SAMPLE OUTPUT :
  
	1. Default input(5 and 2048)
		!(../master/media/default.jpeg)
	   
	2. Left Movement
		!(../master/media/left.jpeg)
	   
	3. Right Movement
		!(../master/media/right.jpeg)
	   
	4. Up movement
		!(../master/media/up.jpeg)
	
	5. Winning game
		!(../master/media/win1.jpeg)
		!(../master/media/win2.jpeg)
		!(../master/media/win3.jpeg)
		!(../master/media/win4.jpeg)

	6. Losing game
		!(../master/media/loss1.jpeg)
		!(../master/media/loss2.jpeg)
		!(../master/media/loss3.jpeg)
		!(../master/media/loss4.jpeg)
		!(../master/media/loss5.jpeg)
		!(../master/media/loss6.jpeg)
 
	7. Unsuccessful output ( Direction enetered was left )
		!(../master/media/unsuccessful_move.jpeg)