# CasinoMastermind
Welcome to the Casino Gaming Platform repository! This project aims to create an immersive and engaging online casino experience, featuring popular games such as blackjack and roulette, along with a sophisticated betting system and user management functionalities.
 
explaition on how to use the program: 

	System Boot:
The user can boot the casino system from a text file or from a binary file.  Choosing the option will allow you to reboot the system with all the relevant casino data.  During the boot, all players registered to the casino will be loaded into the system, and all players' personal information will be transferred and stored into the system. 
	Login:
After loading the system with the casino information, the user will identify himself by user name and password.  In the case of a new player who wants to join the casino, he will be able to create a new user and enter a user name and password in a simple and convenient way.  To sign in to an Admin user, type "ADMIN" and type "Admin". 

Now we divide the possible actions into 2 types of users.  A  Playeruser and an Admin. 
User type Player:
The "Player" user will be shown a menu that is different from that of Admin.  In this menu, the player will be able to perform the following actions: 
	Taking out a loan: 
Any user can apply for a casino loan to continue playing and having fun.  When a user chooses to take a loan, he must be aware of his duty to return the amount he took with an interest rate of 15%. The user can request a loan amount that does not exceed $1000 and as long as he does not have more than 5 open loans. 
	Loan repayment: 
A user can repay the loan that he has taken in a regular manner.  The order of repayment of loans will be in the form of a queue, meaning that the first loan taken will also be the first loan that the user will have to repay.  When choosing this option, the first loan information in the queue will be presented to the user, which means that he has to pay back and the amount that he has to pay back.  The user will be able to repay the loan only if he or she has the necessary amount to repay. 
	Print the player 
In this option, the user can get a detailed snapshot of his financial situation, including details on the number of loans he has taken, the total bet he has made so far, and also his name. 
	Play Blackjack: 
In this game we did a use of a normal deck shuffled (contains 52 cards).
The goal of the game is to beat the dealer's hand without exceeding 21 points.  The card values are calculated based on the value of the number on the card, meaning that the number of the card is the value of its points.  Each card of the royal family (king, queen, prince) is considered to be 10 points.  The value of the ace can be either 1 or 10 points, depending on the player's decision.  
The stages of the game are: 
i.	 Bets -  Before the cards are dealt, the player chooses the amount of his bet. 
ii.	Deal-The dealer deals two cards face up to the player and two cards to himself when one is open and the other is upside down. 
iii.	Player turn- The player has the opportunity to make decisions about his hand.  The player may request to take another card from the deck ("hit") to approach the sum of 21, thus perhaps defeating the dealer or deciding to stay with the current hand ("stand").  The goal is to get as close to 21 as possible without exceeding that number. 
iv.	Dealer turn- After the player has finished his turn, the dealer reveals his card with his face down.  The dealer will take additional cards from the deck until the sum of his hand is 17 or above. 
v.	Determining a winner - after the dealer has finished his turn, the hands are compared.  If the player's hand is closer to 21 than the dealer's, without exceeding 21, the player wins.  If the dealer exceeds 21, and the player "stood" with a sum below 21, then the player wins.  In the event of a draw (the same amount by the player and the dealer), the game ends in a draw or "push".  If the dealer's hand is closer to 21 than the player's without exceeding 21, the player loses. 
vi.	Payments: If the player wins, he gets double his bet.  If he loses, he loses his bet.  If there's a draw, he gets the bet back. 
	Play  Roulette game:
At the beginning of the roulette game, the player chooses his bet size and then chooses the desired bet type.  The types of gambling in roulette include: 
i.	  An even or an odd number, the player chooses whether the drawn number will be even or odd (where 0 is neither even nor odd).  18-to-37. A win doubles the bet 2 times. 
ii.	Black or red  – The player chooses according to which color the lottery number came out.  18-to-37. A win multiplies the bet by 2  .The color distribution is carried out in the following way:
red numbers: You can go 18 to 37. The red numbers are the odd numbers between 1 and 10 and between 19 and 28. And the even numbers are between 11 and 18 and between 29 and 36 numbers. 
The black numbers: You can go 18 to 37. The black numbers are the even numbers between 1 and 10 and between 19 and 28. And the odd numbers are between 11 and 18 and between 29 and 36. 
iii.	Green number - only the number 0 is green.  It is possible to choose which range of a dozen the number came out - doubling the bet 3 times. 

iv.	First third- the numbers 1-12 (odds12/37).
v.	Secound third-the numbers 12-24 (odds12/37).
vi.	Third third-the numbers 24-36 (odds12/37).
vii.	Green or zero  if 0 is outnumbered, the bet will double by 36 (1 chance in 37). 

After choosing the type of bet, a number is drawn between 0 and 36. If the player guessed correctly by the type of bet, he wins accordingly, otherwise he loses the bet.  You can see a standard roulette board on the appendices page. 
	Playing Lucky Wheel: 
The Wheel of Fortune game is a simple and fun game where you have to pay an entrance fee of $65 to participate.  When you select this option, the player's money drops to $65 immediately.
Afterwards the weel spins and stop on a random option :
1.win 75$ 2.win 3.50$ 4.win 200$ 5.win 10$ 6.win 0$.
You can see on the appendix page what the zodiac looks like. 

Admin user: 
An  " Admin" user can perform additional actions that are not available to "Player" users.  When you enter the name using the  password "Admin1", a standard menu will open with standard options like the user "Player", but it will also have unique additional options.  The special actions of this type of user include: 
	Print casino details:
This option prints the casino details, including the casino name, number of registered players and details of all players.  This option allows the manager to get an updated snapshot of the players in the casino and their loans. 
	Add Player:
 This option gives the manager the ability to manually add a new user to the system and give him a username and password. 
	Sort the casino:
The manager can sort the casino players by different categories like a total bet, user name, or current amount of money.  This allows him to organize and arrange the information about the players in the casino in a more convenient way. 
	Player Search:
This option can only be turned on after you've sorted correctly before.  When you select this option, the manager can search for a player by the three categories of the sort.  That is, if the casino players have been sorted by the amount of money they have, the manager will be able to find out if a certain player exists in the system by the amount of money he will bring in.  The manager can see the details of the loans a player has received, the amount of bets he has made so far, and other details relevant to the player's account. 
