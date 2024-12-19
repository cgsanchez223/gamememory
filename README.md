Welcome to the Super Saiyan Matching Game!
- This is for the unit 8.6 Mermory Game Challenge for the Software Engineer bootcamp at Stony Brook University
- Deployment can be found here: https://cgsanchez223.github.io/newgame/
-------------------------------------------------------------

- In unit 8 with learn about DOM (Document Object Model) Manipulation. It is where we combine HTML and JavaScript to listen for user interactions on the page.
- In this assignment, we were tasked to create a matching game using card icons.

-------------------------------------------------------------
How it Works:
- The html page contains several div "id" and "class" elements for the game board pieces.
- First we see the title page and the "START!" button.
- The app.js file uses event listening functions to respond to user clicks on the page.
- Clicking the "START!" button, takes the user to a 5x5 grid.
- Styling and flexbox position is handled with the CSS file.
- The goal of the game is to get 2 matching images.
- The DOM is listening for 2 item clicks. When you click one item, it is programmed to reveal the image. You then get to click a 2nd item. If the 2 items have a matching .gif image file, the cards will remain face up. If the 2 items do not match, the cards will turn back over.
- A shuffle function is used to ensure a random order of the cards with each new play.
- There is also a score timer, which increases with every click made.
- When all cards are flipped over, a game over function is used which records your final score. localStorage is used to keep track of the highest score. If you scored a new high score, the high score will change


-------------------------------------------------------------
Personal Writeup:
- This was the first big JavaScript project I was required to do for the course. I had some fun with the styling and use of gif images. The images I used were gif images from the anime Dragonball Z. These gif images were very common on internet fansites and forums in the 2000s. I thought it would be a neat idea to use them for my gif images. The back of the card also contains an image of a "dragonball" which is also from the show.
- The term "Super Saiyan" is a reference to the anime DragonBall Z.

--------------------------------------------------------------
- This project is optimized for Desktop use.
