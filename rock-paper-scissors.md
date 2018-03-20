- In javascript, select all of your images and loop through them to attach click listeners
- Save the users selection in a variable using the `event` object
- Generate a random number and use that to create a 'computer' selection
  - 0 = rock, 1 = paper, 2 = scissors
- Use 3 if statements with nested if/elseif/else statements to determine the winner
- Use the innerText property of the DOM node for your result div to let the user know if they won or lost or tied

## Extended technical goals
- Create a CSS class called `muted` that sets the CSS property `filter` to `grayscale(100%)`
- Apply that class to ALL images when a selection is made
- Selectively remove that class from the selection that the use has made
- Add an empty `img` tag on the page and update the `img`'s `src` when you know what the computer has selected

## Advanced technical goals
- Embed 3 HTML `audio` tags with sounds representing winning, losing and tying and play them appropriately
- Add a 'Play Again' button that is only visible when the game is over and reloads the game
  - Either by resetting variables to unset state or reloading the page
- Use `setTimeout` to add a delay a 3 second delay to the computer selection process
  - Will probably require you to create 2 separate functions and calling an anonymous function to pass the user selection between the two functions
