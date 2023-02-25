# Random Canvas Pattern

This code defines a canvas element with an id of my-canvas. The JavaScript code uses the getContext() method to get the 2D context of the canvas and sets the canvas size to the size of the window.

The code then defines an array of colors and a squareSize variable that determines the size of the squares to draw on the canvas. The numColumns and numRows variables are calculated by dividing the canvas width and height by the square size and rounding up to the nearest integer.

The code then loops through each square and selects a random color from the colors array using the Math.random() function. The fillStyle property of the canvas context is set to the random color, and the fillRect() method is used to draw a square at the appropriate position on the canvas.

This will generate a random pattern of colored squares on the canvas. You can modify the colors array and the squareSize variable to customize the pattern. You can also experiment with different shapes and drawing methods to create different patterns.
