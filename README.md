# Match Matrix

## Motivation
I always enjoy games that require quick reaction and good memory. This game is a combination of both. The goal of the game is to match the pattern shown on the LED matrix. The pattern will be shown for a short period of time, and the player will have to remember the pattern and match it. The game will get harder as the player progresses.

### Components
1. Joystick (1)
2. 8x8 LED matrix (1)
3. MAX7219 driver (1)
4. Capacitors (2)
5. Potentiometer (1)
6. Buzzer (1)
6. Wires and Resistors

### How to play
When powering up the game, the player will be shown a greeting message. After that, a menu will be displayed, containing options for starting the game, seeing and resetting top 3 scores, settings and some descriptive sections about the game and the author. The player can navigate through the menu using the joystick. The player can select an option by pressing the joystick. The game will start when the player selects the `Start` option. The player will be shown a pattern on the LED matrix for a short period of time. He will have to remember the pattern and match it. The player can move the cursor using the joystick and select/deselect a cell by pressing the joystick. The player can submit the pattern by hold the joystick for a short period of time (around 3s). Then, a message will be shown on the LCD display, stating the accuracy of the drawing, along with the time it took. The drawing will show the player the result: a fast blinking cell means that the cell should have been selected, a slow blinking cell depicts a wrong selected one, and a lit cell means a hit. After pressing the button, if the accuracy and the time qualifies for a top 3 place, the user will be shown on the matrix what place his score will occupy, and he will pe prompted to enter a 3 letter username. The player can navigate through the letters using the joystick and submit the name by pressing it. Top 3 scores are saved, along with the settings of the game (brightness and sounds).

### Setup
<details>
<summary></summary>

![Setup](setup.jpg)
</details>

### [Demo](https://www.youtube.com/watch?v=2hp2ziISHN0)