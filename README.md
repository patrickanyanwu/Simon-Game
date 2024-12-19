<h1 align="center">Simon Game</h1>

This mini project was made to dsiplay my javascript skils to develop games such as the Simon memory game. HTML, CSS and Javascript was used for this project.

The game run is shown below and can be accessed <a href="https://simon-game-patrick.netlify.app/">here</a>.

https://github.com/user-attachments/assets/c8be3487-c7e0-47a4-a59b-22ee658ff806

<h3>How the game works</h3>

When the site loads the page now listens for any key to be pressed, when that key is pressed it triggers the function to start the game. A random number is then generated between 0 and 3 to chose a random square to add to the sequence.
The random sequence is stored in an array and every time a user then makes their guess their sequence is stored in another array and is compared to the computers random array after every level. After every level the users array of guesses resets and if any guess is wrong then the game ends. Event listeners were used to detect clicks and keypresses, timeouts were used to create the flashing effect, and classes were added to the html elements to show the flashing colour.
