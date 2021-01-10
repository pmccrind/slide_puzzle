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

# Lets begin!

## Part I Setting up

1.) Fork and clone this repo to your local machine.

2.) Make an (.html) file in the root of the directory, ie not in one of the provided folders. Making sure that it has:

  * HTML tags
  * Head tags
  * Body tags

3.) Link the CSS (in the CSS folder) file to your HTML file, in between the head tags.

4.) Link the provided JS file to your HTML file, in the between the head tags.

5.) If you have a custom image then save that image to the Images folder now.

## Part II HTML Setup

1.) Change the header of your HTML file with the title tag.

2.) Make a header to be displayed above your slide puzzle using the header size of your choice.

3.) In the opening body tag add the following ``` onLoad() = "shuffle();" ``` this allows the game board to be shuffled as the page is being loaded.

## Part III Game Board Setup

1.) Make a center tag, and make all other tags inside of the center tag.

2.) Make a div tag and give the tag an id of "table" and also give it a style of ```display: table```.

3.) Make a div tag inside of table div, giving it the id of "row1" give it the class of "rows".

4.) Make three div tags inside of row one with id's of, "cell11", "cell12", "cell13" and giving them each a class named ```tile1```, ```tile2```, and ```tile3```.

  * For each of the divs add ```onClick = moveTile(X,Y);``` where the X and Y values are equal to the first and second number that are in the id's of each of the cells. For example for the first cell it would be ```onClick = moveTile(1,1);```. The X value is the row number and the Y value is the column number.

5.) Repeat steps 3 and 4 twice making 2 more rows with id's of "row2", and "row3", and giving the inside divs the correct cell id numbers and correct class names. Ensuring that the ```onClick = moveTile(X,Y);``` is changed for each div.

  * Note the id and class names here will be referenced in later parts, if you chose to name them something else you will need to keep this in mind.

Here is how the first div that should be a cell should look: ```<div id = "cell11" class="tile1" onclick="moveTile(1,1);"></div>```.

## Part IV CSS Styling

1.) Give your webpage a background color or colors.

2.) For you header:

  * Make the text be centered on the page.
  * Increase the size of the font of the header.
  * Change the color of the text of your header.

3.) Reference the rows class and give it the following: ```display: table-row;```

4.) Reference each of tiles class (ie tile1 ... tile9) and give them the following properties:

  ```
  display: table-cell;
  width: 120px;
  height: 120px;
  border: 3px solid white;
  background: url(../Images/icspark_logo_360_360.PNG);
  ```

  * Note if you have a custom image and it is saved in the Images folder then change the text after ```../Images/your_filename_here.jpg```
  * If you image is not 360 by 360 but it is equal length and width then divide the length by 3 and replace the width and height values with that value instead.
  * Additionally, may want to change ```border``` to be a different color, if you have a mostly white image for example it be better to change it to a darker color.

5.)

## Part V JavaScript



Congratulations!! You have made your very own slide puzzle!


## Stretch Goals

* Make a button below your table that when pressed will randomize the game board
* Display above the game board but below the heading "You Win!" when the puzzle is complete.
