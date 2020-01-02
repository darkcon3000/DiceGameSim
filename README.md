Run the .py file, the parameters for running the simulation are listed below: 

# DiceGameSim
##Here you actually simulate the betting
#Syntax: bettingSim(playerCount,funds,intialWager,wagerCount,bettor)
##Here are the parameters:
# playerCount: number of players to run the simulation with. 
# funds: number of starting funds for each players
# initialWager: initial wager for each player
# wagerCount: essentially the game length, how many wagers/bets each player can make at a maximum if they don't go broke
# bettor: this is where you choose which betting strategy to simulate.
    # simpleBettor, this bettor bets his initial wager every time
    # doulbeBettor, this bettor bets double his past wager if he loses.
        #if he doesn't have enough money to double his past wager he goes all in
