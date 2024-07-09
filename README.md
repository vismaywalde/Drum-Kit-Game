# Drum Kit Game

Welcome to the Drum Kit Game! This project allows you to play different drum sounds by clicking on buttons or pressing specific keys on your keyboard. It's a fun and interactive way to learn and enjoy music!

## Project Structure

The project consists of the following files:

1. `index.html`: The main HTML file that sets up the structure of the web page.
2. `styles.css`: The CSS file that styles the web page (not provided, but expected to be part of the project).
3. `index.js`: The JavaScript file that handles the logic for playing drum sounds and adding animations.

## Getting Started

To get started with the Drum Kit Game, simply open the `index.html` file in your web browser.

### HTML Structure (`index.html`)

The HTML file sets up a basic structure with buttons for each drum sound. Each button has a class of `drum` and a specific letter representing the drum sound it plays.

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>Drum Kit</title>
  <link rel="stylesheet" href="styles.css">
  <link href="https://fonts.googleapis.com/css?family=Arvo" rel="stylesheet">
</head>

<body>

  <h1 id="title">Drum 🥁 Kit</h1>
  <div class="set">
    <button class="w drum">w</button>
    <button class="a drum">a</button>
    <button class="s drum">s</button>
    <button class="d drum">d</button>
    <button class="j drum">j</button>
    <button class="k drum">k</button>
    <button class="l drum">l</button>
  </div>

  <footer>
    Made by Vismay
  </footer>

  <script src="./index.js"></script>
</body>

</html>


JavaScript Logic (index.js)
The JavaScript file handles the logic for playing the correct drum sound when a button is clicked or a key is pressed. It also adds a temporary animation to the button to give visual feedback.

How It Works
When a button is clicked or a corresponding key is pressed, the makeSound function is called to play the appropriate sound.
The buttonAnimation function adds a pressed class to the button for a brief moment to create a visual effect.
The sounds are stored in the sounds directory (not provided, but expected to be part of the project).
