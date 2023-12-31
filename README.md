# PORTFOLIO PROJECT - 3

# BATTLESHIPS

 Battleship or battleships as it is also known is a strategy type guessing game for two players (or in this case 1 player and the computer). It is played on ruled grids on which each player's fleet of battleships are marked. The locations of the fleets are concealed from the other player.

 
<img src="assets/amiresponsive.png">  

[Am I Responsive](https://amiresponsive.co.uk/)



## INITIAL IDEA CONCEPT

 My initial idea for the project was to create the traditional game of battleships where the user will play against the computer.The computer will randomly select where they place their ships before the game starts. The user and the computer will then take it in turns to try and guess where they have placed their ships.

 * Here is a link to the [final project](https://battleship-1987-509de5bf3d9c.herokuapp.com/)


## Flowchart

<img src="assets/flowchart.png">

## USER STORIES

1. As a user, I want to be able to add my name.
2. As a user, I want to be able to place the ships on the board on the slots selected.
3. As a user, I want to be able to see my fleet on the game board.
4. As a user, I want to be able to see how many ships are remaining after every turn.
5. As a user, I want to be able to see on the board when I hit or miss the computer fleet.
6. As a user, I want to be able to see the computers choices and the result.
7. As a user, I want to be able to see who has won the game.
8. As a user, i want to be able to play the game again once the game is complete.


## FEATURES

### Welcome Message

* Shows a welcome message to the user.

<img src="assets/welcome-message.png">

### Enter your Name

 * The User is able to enter the name that will be displayed in the game.

<img src="assets/enter-name.png">

### Place the fleet

 * The user is able to place 5 ships on the board.

 <img src="assets/user-ship-entry.png">




### User Turn

 * The user selects a slot on the board trying to guess where the computer fleet is.
 * Displays a message to the user as a result of their turn.
 * Displays the board with an '0' for missing the ship and an 'X' for destroying a ship.

 <img src="assets/user-result-of-shot.png">
 <img src="assets/ship-hit-message.png">
 <img src="assets/missed-message.png">


### Remaining ships

 * Displays the remaining ships after every turn by the user and computer.

 <img src="assets/ships-remaining.png">

### Computer Turn

 * Displays the guess made by the computer.
 * Displays a message with the result of the guess made by the computer.
 * Displays the result after the computer's turn.

<img src="assets/computer-turn.png">

### Final Result

 * Displays a message with the winner of the battle once the user or computer has destroyed the fleet of the other player.

<img src="assets/game-won-message.png">

### Restart game 

 * Asks the user to play again or to end the game
 * User can decide to play again or to end the game
 * Restart the games by asking the user to insert their name again
 * If the user chooses not to play again then a message thanking them for playing will appear.

<img src="assets/play-again-message.png">
<img src="assets/thanks-for-playing-message.png">


### User Input Validation

 * Displays a message to the user for a wrong input.

<img src="assets/entry-error.png">
<img src="assets/shot-entry-already-message.png">
<img src="assets/wrong-data-input-message.png">

### Future features:

 * Add the abilty to make the game a 2 player game. This would then allow friends to play against eachother rather than the user only having the option to player against the computer.

 * Add a pyfiglet feature at the top of the page for the header to make the game more appealing on the eye.

 * Add a feature that would allow the player to decide the size of the board in which they could play on.

 * Adding a board size bigger then the current one would  allow the user to have more ships on the board.

 * Adding a feature to allow a different amount of ships to play with.



### Typography

 * Standard terminal font which cannot be changed

# TESTING

## User story testing

1. As a user, I want to be able to add my name.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Enter your name | Type in your name when asked to do so | The name of the user will be displayed during the game | Works as expected |

2. As a user, I want to be able to place the ships on the board on the slots selected.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Place the fleet | Place 5 ships on the board | The user is able to place 5 ships on the board on the preferred slots | Works as expected |

3. As a user, I want to be able to see my fleet on the game board.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Display user's fleet | The ships positioned on the preferred slots by the user will be displayed on the board | The user is able to see the 5 ships on the board | Works as expected |

4. As a user, I want to be able to see how many ships are remaining after every turn.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Remaining ships | Displays the remaining ships after every turn | Displays the remaining ships after every turn | Works as expected |


5. As a user, I want to be able to see on the board when I hit or miss the computer fleet.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| User Turn | The user selects a slot on the board trying to guess where the computer fleet is | Displays a message to the user as a result of the turn | Works as expected |

6. As a user, I want to be able to see where the computer choices and result.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Computer Turn | The computer chooses randomly a slot on the board to guess where the user fleet are located | Displays the guess made by the computer, and the result | Works as expected |


7. As a user, I want to be able to see who won the game.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Final Result | The user or the computer has destroyed the last ship from the opponent | Displays a message with the winner of the battle once one of the player has destroyed the fleet of the other player. | Works as expected |

8.  As a user, i want to be able to play the game again once the game is complete.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Final Result | The user has the option of restarting a new game once the game has ended | Displays a message of do you want to play again (Y for yes and N for no)| Works as expected |


## Validation

### PEP8 Online Validation

PEP8 online was used to check the code for PEP8 requirements.


![PEP8 Results](assets/pep8-validation.png)

## Solved bugs and errors

* Throughout the development of this project, several automated errors have been fixed eg:

  * Indentation errors
  * Not enough whitespace between functions
  * No new line at end of file
  * Syntax errors
    


## Unsolved bugs and errors

 * No bugs or errors are present

# TECHNOLOGIES

## DEVELOPMENT

 * The project was written and tested using [Gitpod](https://gitpod.io/)
 * The project uses [Github](https://github.com/) for utilising git version control
 * The project was deployed via [Heroku](https://heroku.com/)

## LANGUAGES USED

 * Python 3

## LIBRARIES USED

 * [random](https://docs.python.org/3/library/random.html) to generate the computers placement of ships
 * [time](https://www.programiz.com/python-programming/time) for text delays between user and computer moves

# DEPLOYMENT

## Heroku

* This Game was deployed using [Heroku](https://heroku.com/) with the following the steps:

1. Navigate to [Heroku.com](https://www.heroku.com/) and log-in or create a new account.
2. On the top right hand side, click the 'New' button.
3. Inside the dropdown menu, select 'Create new app'.
4. Create a new name for your app (making sure the name chosen is available) in this case it is `battleship-1987`.
    App names can only be in lower-case letters, numbers and dashes.
5. Select your region, in this case, `Europe`.
6. Click on the `Create App` button.  
7. This will create your app in Heroku and take you to the [Heroku](https://heroku.com/) dashboard.
8. Navigate to the settings tab and scroll down to the button `Reveal Config vars`.
9. Replace the word `KEY` and enter `PORT` and then replace the word `VALUE` and enter `8000` then click on the `Add` button.
10. Below `Config vars` is `Buildpacks`. Click the `Add Buildpack` button.
11. In the pop up window, select `python` and save changes.
12. Repeat this again but this time selecting `node.js` and save the changes.
13. It is `important` to make sure the buildpacks are in the correct order 
    with `Python` being at the top and `node.js` bottom. If they are not in the correct order, you can drag them into the right order.
14. Next, navigate to the `Deploy` tab at the top left side.
15. Select `Github, 'connect to github'` as the deployment method.
16. Search for the Github Repository in the search field (in this case `battleships`) and click `Search`.
17. When the search is complete, click `connect`.
18. Once your repository is connected to [Heroku](https://heroku.com/), Click the `Enable Automatic Deploys` button for automatic deployment.
19. Alternatively you can manually deploy by selecting a branch to deploy from and clicking `Deploy Branch`.
20. If you choose to `Enable Automatic Deploys`, [Heroku](https://heroku.com/) will build a new version of the app when a change to `gitpod` is pushed to `Github`.  
21. Manual deployment allows you to update the app whenever you click `Deploy Branch`.
    In the case of this project, I chose to `Enable Automatic Deploys` to ensure the code was deployed straight away at each push from `Gitpod`.
22. Once the build process is complete (this can take a few seconds) you will then be able to view the live app by clicking on the button `View`
    below `Your app was successfully deployed`.

## Version control

* These commands were used for version control during project:

    * git add `example filename` - to add files before committing
    * git commit -m `"example message"` - to commit changes to the local repository
    * git push - to push all committed changes to the GitHub repository
    * git branch - to see which branch currently working on
    * git pull - to pull all code into main branch once the feature branch had been merged and deleted
    * git status - to see if the branch currently working on is upto date or if the are any unstaged
    * git log --oneline - to see the last commit
    * git commit --amend - to amend the most recent commit message

## How to create a branch/Tag of main:

If you need to `BRANCH` off of the main repository:

1. If you have not already, login in to [GitHub](www.github.com) and go to https://github.com/jamieroche1987/battleships
2. On the left side of the screen underneath the nav links, click the drop down box `Main`
3. Inside the box you will see `Create new branch/tag`
4. Inside the text box, enter the new branch or tag name i.e., `Features`
5. Below the Branches Tags tab, you will see `Create branch: Features from "main"`
6. Click on `Create branch: Features from "main"` and you will be taken to the new branch page you just called `Features`

## How to fork a repository:

If you need to `FORK` a repository:

1. If you have not already, login in to [GitHub](www.github.com) and go to https://github.com/jamieroche1987/battleships
2. In the top right corner, click `Fork`
3. The next page will be the forked version of https://github.com/jamieroche1987/battleships but in your own repository

## How to clone a repository:

If you need to make a clone of this repository:

1. Fork the repository https://github.com/jamieroche1987/battleships using the steps above
2. Above the file list, click `Code` (Usually green at the top right of the code window)
3. Choose if you want to clone using HTTPS, SSH or GitHub CLI, then click the copy button to the right
4. Open Git Bash
5. Change the directory to where you want your clone to go (your own github)
6. Type `git clone` and then paste the URL you copied in step 4
7. Press `Enter` to create your clone

## How to make a local clone:

If you need to make a local clone:

1. If you have not already, login in to [GitHub](www.github.com) and go to https://github.com/jamieroche1987/battleships
2. Under the repository name, above the list of files, click `Code`
3. Here you will have two options, `Clone` or `Download` the repository
4. You should close the repository using HTTPS, clicking on the icon to copy the link
5. At this point, you can launch the `Gitpod workspace` or choose your own directory
5. Open Git Bash
6. Change the current working directory to the new location of where you want the cloned directory to be
7. Type git clone and then paste the URL you copied in step 4
8. Press Enter, to create your local clone to your chosen directory

## CREDITS AND REFERENCES

### CODE

* Dan for his input on how to fix certain errors of code that i was struggling with.
* Jamie for his help in identifying errors in my indentation that i hadnt seen.
* [W3Schools](https://www.w3schools.com/) for information on python functions and how they can be implemented
* [Stackoverflow](https://stackoverflow.com/search?q=battleship+python&s=f5b5700f-8508-47e8-8ac9-e2b10fccbd7e) for methods of how to implement certain features of python for my projectas well as how to correct incorrect coding errors.
* Everyone on the Code institute Slack community for all the help and guidance with code queries i had when i was building this project.



## ACKNOWLEDGEMENTS:

* My partner Runa for her continued support while this project has hit alot of issues along the way causing alot of stressful days. Her positivity and encouragement has been something i needed a few times along the way when it seemed all was lost.
Thank you Runa i truly appreciate it 
* My mentor Alex for always being supportive and giving me great advice when issues kept arising along the journey of building this project. Thank you Alex for always being there when times weren't the easiest.
* Jason from Tutor assistance who pointed me in the direction of Gitpod when my CodeAnywhere workspace decided it was not going work half way through my project. Thank you Jason
* Kieron from Student care who extended my deadline day after not having access to internet for 2 weeks during the learning and building of this project. Also taking into account i didnt have any access to my workspace when i was buliding my project for several days after i finally managed to access internet again. Thank you Kieron for you understanding and help to give me the best chance i could to complete this project.
