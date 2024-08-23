
# Apple Pie

Project for IPad from "Develop in Swift Fundamentals".

In this simple word-guessing game, each player has a limited number of turns to guess the letters in a word. Each incorrect guess results in an apple falling off the tree. The player wins by guessing the word correctly before all the apples are gone.


## Tasks
 
-  Build the Interface
-  Beginning a Game
-  Update Game State 
-  Create Revealed Word
-  Handle a Win or Loss
  
<img width="606" alt="Screenshot 2023-10-04 at 1 15 59 PM (1)" src="https://github.com/user-attachments/assets/71bbf9c8-7427-4668-9ff0-698a551fd64b">

## Part 1: Building the Interface
The user interface is created within Main.storyboard. Some code to link up the IBOutlets and IBActions are included in the viewcontroller.
Codes are incrementally added from Part 2 to Part 5.
## Part 2: Beginning a Game
It includes setting the basic properties of the game. It also create the Game model as a separate Swift file. It also include the code that update the tree image when letters are guessed.
## Part 3: Update Game State
This part describes the code that handle the game as it progresses. When buttons are tapped, the game state, together with the user interface needs to be updated.

A bug in the iBook’s code causes the game not to update the UI. This source code includes the statement updateUI() in the buttonTapped() IBAction of the viewcontroller.
## Part 4: Create Revealed Word
This part add the code to display the guessed letters in correctWordLabel. A new property in the Game model called the formattedWord is created for displayed to the view.
## Part 5: Handle a Win or Loss
The last part adds the code to restart a game when the player either guessed the word correctly or wrongly.
