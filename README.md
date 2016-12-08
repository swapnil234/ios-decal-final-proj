#Bear Jump

##Authors
* Swapnil Thombre
* Neil Gupta
* Priya Agarwal 

##Purpose
To make a fun game themed around the Stanford v Cal rivalry as well as the
recent public funds scandal with Chancellor Dirks.


##Features
* Ability to tap on screen to make bear jump 
* Ability to view score and send to friends over messages
* Will show a “lost” screen when you hit a tree
* Can keep track of score real time as the longer you stay alive and more public
funds you collect, your score increases


##Control Flow
* User opens app and goes to introduction screen which shows options to play 
game or view previous high scores 
* User can click on high scores tab to see a list of scores they’ve had
* User can click on play to start a new game which moves it into the game screen
* On game screen, user will be presented with a bear that is moving to left with
trees being populated on the 
* platform. On tap, the bear will jump. 
* If bear hits tree and dies, the game will exit to “summary screen” where the 
stats like score will be presented and the option to share will be presented 
and Dirks face will come up saying he got away with the public funds.
* On exit, the game will return to original screen 

##Implementation
###Model:
* Bear.swift
* Tree.swift
* PublicFunds.swift 

###View:
* StartScreenView
* GameView
* EndGameView
* ScoresView

###Controller:
* StartScreenViewController
* GameViewController
* EndGameViewController
* ScoresViewController 
