# Memory Card Game

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/I-SatyamPrashar/Memory-Card-Game?style=social)](https://github.com/I-SatyamPrashar/Memory-Card-Game/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/I-SatyamPrashar/Memory-Card-Game?style=social)](https://github.com/I-SatyamPrashar/Memory-Card-Game/network/members)

## Overview

This is a fun and engaging Memory Card Game built using HTML, CSS, and JavaScript. The game challenges players to test their memory skills by matching pairs of hidden cards. It provides a simple yet entertaining way to pass the time and exercise your brain.

## How to Play

1.  When the game starts, all cards are face down.
2.  Click on a card to reveal the image underneath.
3.  Click on a second card to reveal its image.
4.  If the two revealed cards have the same image, they remain face up (matched!).
5.  If the two revealed cards have different images, they are flipped back face down after a short delay.
6.  The goal of the game is to match all pairs of cards in the minimum number of moves.
7.  Once all pairs are matched, the game ends.

## Features

- **Interactive Gameplay:** Provides an engaging and responsive user experience.
- **Random Card Arrangement:** The cards are shuffled randomly each time the game starts, ensuring a different challenge every play.
- **Simple User Interface:** Clean and intuitive design for easy understanding and playability.
- **Visual Feedback:** Cards flip to reveal images, stay open on a match, and flip back on a mismatch, providing clear feedback to the player.
- **End Game Condition:** The game clearly indicates when all pairs have been successfully matched.
- **Scoring (Potential Future Feature):** While not currently implemented, the foundation is there to potentially track the number of moves or time taken.

## Technologies Used

- **HTML:** Provides the structural foundation for the game board and cards.
- **CSS:** Styles the game elements, including card appearance, layout, and visual feedback.
- **JavaScript:** Handles the game logic, including card flipping, matching, shuffling, and game state management.

## Getting Started

To play this game locally:

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone [https://github.com/I-SatyamPrashar/Memory-Card-Game.git](https://github.com/I-SatyamPrashar/Memory-Card-Game.git)
    cd Memory-Card-Game
    ```
2.  **Open the `index.html` file in your web browser.**

   The game should start automatically in your browser.

## Project Structure
Memory-Card-Game/
├── index.html
├── style.css
└── script.js
├── images/            (Directory containing the card images)
│   ├── image1.png
│   ├── image2.png
│   ├── ...
└── README.md
## Customization

You can customize this game by:

- **Changing the Card Images:** Replace the images in the `images/` directory with your own set of images. Make sure to update the JavaScript (`script.js`) to reflect the number of pairs and the image sources if necessary.
- **Modifying the Game Board Size:** Adjust the HTML structure and CSS styles to change the number of cards displayed on the game board. You'll likely need to update the JavaScript to handle the new number of cards.
- **Styling:** Modify the `style.css` file to change the appearance of the cards, the game board, and other visual elements.
- **Adding Features:** Enhance the game by adding features like:
    - Tracking the number of moves.
    - Implementing a timer.
    - Adding difficulty levels (by changing the number of cards).
    - Storing high scores.


## Contact

- **Author:** Satyam Prashar
- **GitHub:** [https://github.com/I-SatyamPrashar](https://github.com/I-SatyamPrashar)
- **Email:** satyamprashar2000@gmail.com

Feel free to contribute to this project by submitting pull requests or reporting issues!
```
