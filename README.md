# Etch-A-Sketch
Breakdown of Etch a Sketch functionality

  `// Variable Creation`
1) Create variables to grab "user input", "grid container", "reset button".

  `// Function Declarations`
2) Make a function to create a grid consisting of 256 squares (16x16). This is the default grid and will be reset to this size when prompted.
3) Make a function to update the grid with the users input. This will set the inner html to 0 to avoid staking divs on divs from the original grid and set the grid templates for columns and rows to the user generated input. 
  -Then, to fill the grid to the correct amount of squares, a for loop is used to multiply the user input x user input. We create the div element, add it the class value of 'square', then append each div to the grid. Log the user input to the browser.
  
  `// Event Listeners`
4) Create a variable that represents each square, attach event listener on mouseover that replaces the square class with the color class. 
5) Create an event listener that will change the grid after the user inputs a quantity (change event, updateGrid function).
6) Create an event listener that resets when a user clicks the reset button. The innerhtml will revert to "", the user input resets, the grid-template propertys are set to 16x16, and the function will call the create grid function. 
7) Lasty createGrid is called at the end for intialization. 
