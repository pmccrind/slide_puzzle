# Welcome to Slide for Lyfe!

Slide puzzles are easy to see how it is supposed to look like but you may find getting the pieces in the right positions more difficult. By following this guide you can make your very own slide puzzle!

## Objective

Using JavaScript (JS) for tile movement, CSS positioning to display the tiles in a table, CSS to style the tiles making it look like puzzle pieces, and HTML to display the page.

## Prerequisites

* Github, fork, and clone
* Atom Text Editor (or Editor of your choice)
* HTML structure
* Linking of files using paths to your document, to include relative and absolute paths
* CSS Styling by ID and Class
* CSS positioning using background-position
* CSS style display options
* OPTIONAL: An image that is equal in length and width, that is also divisible by 3 (ie  an image that is 360x360 pixels, because 360/3 = 120)

## Provided

* Folder structure
* Game Logic
* Default image

Lets begin!

## Part I Setting up

1.) Fork and clone this repo to your local machine.

2.) Make an (.html) file in the root of the directory, ie not in one of the provided folders. Making sure that it has:

  * HTML tags
  * Head tags
  * Body tags

3.) Link the CSS (in the CSS folder) file to your HTML file, in between the head tags.

4.) Link the provided JS file to your HTML file, in the between the head tags.

5.) If you have a custom image then save that image to the Images folder.

## Part II HTML Setup

1.) Change the header of your HTML file with the title tag.

2.) Make a header to be displayed above your slide puzzle using the header size of your choice.

## Part III Game Board Setup

1.) Make a div tag give the tag an id of "table" and a style of "display: table".

2.) Make a div tag inside of table div, giving it the id of "row1" give it the class of "rows".

3.) Make three div tags inside of row one with id's of, "tile1", "tile2", "tile3" giving them all the class of "tiles".

4.) Repeat steps 3 and 4 twice making 2 more rows with id's of "row2", and "row3", and giving the inside divs the correct tile id numbers and correct class names.

  * Note the id and class names here will be referenced in later parts, if you chose to name them something else you will need to keep this in mind.

## Part IV CSS Styling

1.) Give your webpage a background color or colors.

2.) Align your header to be in the center of the page.

3.) Reference the rows class and give it the following:
  ```
  display: table-row;
  ```

## Part V JavaScript



Congratulations!! You have made your very own slide puzzle!


## Stretch Goals

* Make a button below your table that when pressed will randomize the game board
* Display above the game board but below the heading "You Win" when the puzzle is complete.

*** Work in Progress ***
