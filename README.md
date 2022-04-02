# Mock Test - UI-Basics

## Test Instructions
* In the test folder in this repository, there are both html and css files as well as an images folder. These files contain the foundations of a web page for a chess club.
* The task is to follow the instructions below to create a responsive page.
* You can see what the completed page should look like [here](https://dciforks.github.io/UIB-mock-test/)
* Enjoy! 


## Colour palette

For information, the colours used in the demo are:
* peru
* wheat
* white
* black
* linen
* sienna
* bisque
* maroon

## Header, main and footer

1. Use the chess_set.jpg image as a background for the header.
2. Use a linear gradient to make the background image lighter.
3. Make the header always visible at the top, unless the height of the viewport is less than 720px, in which case the header should scroll with the page.
4. Move the footer to the end.
5. Make the footer 2rem high.
6. Make the footer visible at all times.
7. Add an unordered list to the footer, add three list items to it.
8. Each list item should have an anchor link nested inside. Only add an "#" symbol to the `href`.
9. Find three social media icons to place inside the anchor links, e.g. instagram, linked in, twitter.

## Cocktails
4. For the four square cocktail images:
   * Make the divs with the cocktail class square
   * Show the h3 header centered at the top of the div, over the image
   * Show the ul ingredients at the bottom of the div, over the image
   * For the dark images (Fisher and Spassky), show the h3 and ul elements in white
   * For all text, provide a shadow outline in a contrasting colour, to improve readability
5. When the width of the viewport is greater than 450px:
   * Show the cocktails in two rows, with two side-by-side images.
   * Swap the location of the last two images show that the images create a checkerboard pattern.
   * Ensure that there is no gap between the two rows of images.

## Chessboard
1. Make the chessboard the full width of the viewport unless the viewport is wider than 450px.
2. Make the chessboard a maximum of 450px wide.
3. Create a checkerboard pattern in the chess-board table.
4. Make the table cells that represent the chess-board square.
5. Create a coloured strip around the central chess-board, where the column letters and row numbers appear.
6. Create a darker border on both sides of this strip.

## Competition
1. Using CSS only  and ***without altering the HTML*** make the title for the competition appear with a capital letter at the beginning of each word, like this: `Thirsty Thursday Offer`.

## Form
1. Create a form to enter the competition:
   * Header text: Entry Form
   * Instructions text: To enter the competition, send us your name, email address and the moves that will win for White.
   * Fields
     1. Name
        + Text: Name
        + Placeholder: your name goes here
     2. Email
        + Text: Email
        + Placeholder: your.email@goes.here
     3. Entry data
        + Text: Moves in algebraic notation
        + Placeholder: your moves go here
     4. Bonus header (no input required)
        + Text: Bonus to win a cocktail for one of your mates
     5. Optional field
        + Text: Give the name of this type of mate
     6. Button
        + Text: Win a Free Cocktail
2. Make the entry form the same width as the chess-board (i.e. the full width of the viewport, or a maximum width of 450px).
3. There should be a reasonable margin between the button and the footer when the page is fully scrolled. 
### Validation
4. Fields 1, 2 and 3 are required.
5. Field 1 (name) must contain at least 2 characters.
6. Field 2 (email) must contain a valid email.
7. Field 3 (moves) must contain at least 12 characters.
8. If a field is invalid (and not empty):
   + Show an asterisk at the top right of the field
   + Show a coloured background while the user is typing
   + Show a dotted border if the user around the invalid field if the user typing elsewhere.
   
   **NOTE:** input fields by definition do not have a `value` so using the `:empty` pseudoclass will not have any effect. 
9. Hide the asterisk for any field which is valid.

## Responsivity
1. As already noted, when the viewport is less than 450px wide:
   * The cocktails should appear as a column
   * The chess-board should be the full width of the viewport
   * The form should be the full width of the viewport.
2. When the viewport is wider than 450px:
   * The cocktails should appear in two rows and two columns, creating a checkerboard pattern.
3. When the viewport is wider than 720px (which just happens to be the width of the `chess-set.jpg` image), the contents of the page should remain limited at a width of 720px, with black margins either side.

## Bonus

Choose an approriate image to illustrate the second paragraph, and show it to the right of the text, when the viewport is wider than 450px.