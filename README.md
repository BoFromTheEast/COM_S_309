
# COUP_Mobile
A mobile game based on Card game COUP.

## Description
The main objective of this project is to create an interactive COUP card game. The game is built using Java in IntelliJ IDEA, Maven, Android Studio, Gradle, and MySql and tested using Postman.

## How will the app work?
1. The back end of our project will be implemented with Java and Spring Framework. We will create a class hierarchy for cards, as each card will have its own abilities. We will implement the game logic in a turn-based manner. Here is an example:
    - All users will start with two random cards and two coins.
    - Each round will follow in a clockwise manner, with each turn giving the player an ability to take a coin, use their character abilities, or eliminate a player if they accumulate enough coins.
    - After a user makes a decision on their turn, all users have the ability to block the current player's move with their respective character, or call their bluff.
    - In the event of a bluff, users will have to show their card and draw a new one, or lose their card due to bluffing.
    - Then it becomes the next player's turn.
    - A user wins when they are the last one remaining with cards.

<!--##
## Visuals
Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.

## Installation

 Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.
-->

## Roadmap
Fully working implementation in Android and moving the game into IOS using Swift. Possible implementation of the web version.

## Team
Composed of 4 dev team including myself. 2 Frontend devs using Android Studio and Gradle, and 2 Backend devs using IntelliJ Studio, and Maven. 

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

<!--## License
For open source projects, say how it is licensed.
-->
## Project status
In Development.
