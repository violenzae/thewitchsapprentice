# The Witch's Apprentice

#### _2D Roguelike game built in unity_

#### By: **Rachel Schieferstein, Patrick Delaney, Alex Skreen, Mariam Alaeddin**, April 6-9, 2020

## Description

_This is an action adventure game that brings the user through multiple levels where they must find hidden items and defeat enemies to reach the witch!_

## Specification user stories:
| Specification | Example Input | Example Output |
| ------------- |:-------------:| -------------------:|
| If user clicks 'start' the game will load the first level | 'start' click | Game displays 'day 1' then loads random level |
| if user clicks the left key or the 'a' key the character will move left | 'left' or 'a' click | Character moves left by 1 square |
| if user clicks the right key or the 'd' key the character will move right | 'right' or 'd' click | Character moves right by 1 square |
| if user clicks the down key or the 's' key the character will move down | 'down' or 's' click | Character moves down by 1 square |
| if user clicks the up key or the 'w' key the character will move up | 'up' or 'w' click | Character moves up by 1 square |
| if user click the escape key they will pause the game | user clicks 'escape' | Game displays pause screen including 'Resume' 'Menu' and 'Quit buttons' |
| if user clicks the 'Resume' button while in the puase menu the game will resume | user clicks 'Resume' | Game resumes and pause screen disappears |
| if user clicks the 'Menu' button while in the pause menu the game will bring them back to the initial menu screen | user clicks 'Menu' | Game goes back to the initial menu screen and the pause screen dissappers |
| if user clicks the 'quit' button while in the pause menu the game will bring quit | user clicks 'quit' | Game quits |
| if user attempts to move in any direction, their food will decrease by 1 point | user attempts move | food: 60 |
| if the user moves towards an internal wall, the user will hit the wall | user hits an internal wall | internal wall shows damage |
| after three hits, an internal wall will crumble and disappear | user hits a wall 3 time | Wall crumbles them dissappers
| if the user moves to a space occupied by an item, the user's food will go up by 20 points | user moves onto a space occupied by an item | +20! Food: 80 |
| if the user moves to a space occupied by an enemy, the user's food will go down by 20 points | user moves onto a space occupied by an item | -20! Food: 60 |
| if the user moves onto a space containing a clover or a unicorn horn they pass that level | user moves onto a space containing a clover or a unicorn | Game displays 'day 2' then loads a random level |
| if the user's food reaches 0 they will "starve to death" | food: 0 | Game displays "after 2 days, you starved" then brings you back to the main menu|




## Setup/Installation Requirements

### Install Unity

* Navigate to https://store.unity.com/download
* download the newest version of Unity by clicking 'download unity hub'
* follow setup instructions
* create your unique unity id

### Clone this repository

_Enter the following commands in Terminal (macOS):_
* ``cd desktop``
* ``git clone`` followed by the URL to this repository
* ``thewitchsapprentice/run/witch.exe``

_Enter the following commands inPowerShell (Windows):_
* ``cd desktop``
* ``git clone followed by the URL to this repository``
* ``cd thewitchsapprentice``
* ``cd run``
* ``witch.exe``

### Open this repository in Unity

* Open unity hub
* click the "add" button
* select the newly cloned repository

### Play game in Unity

* Once project is added into your unity hub click on it
* You will see three tabs at the top center of the unity screen
* Click "game"
* Click the play button and allow it a few seconds to load

_To view/edit the source code of this application, open the contents of the thewitchsapprentice.Solution directory in Unity

## Technologies Used

* Git
* C# v7.3
* Visual Studio Code 1.43.1
* Unity 2019.3.7f1
* [Dungeon Crawl Tiles](https://opengameart.org/content/dungeon-crawl-32x32-tiles)
* [Roguelike Tutorial](https://www.youtube.com/watch?v=Fdcnt2-Jf4w)
* [Pause Screen Tutorial](https://www.youtube.com/watch?v=JivuXdrIHK0)
* [Start Menu Tutorial](https://www.youtube.com/watch?v=zc8ac_qUXQY)
* [Monsters Creatures Fantasy by LuizMelo](https://luizmelo.itch.io/monsters-creatures-fantasy?download)



## License

Licensed under the MIT license.

&copy; 2020 - Rachel Schieferstein, Patrick Delaney, Alex Skreen, Mariam Alaeddin