# codeRefactor

## Description

The purpose of this project is to practicce refactoring code, which is improving pre-existing code without changing it. This process includes making the code easier to read for the next person who may have to read it, consolodating repeating CSS code, and making the website more accessible overall. 

## User-Interface accessability problems

When opened through a browser the starter-code was shown to have a broken link. There were three links at the top of the page that were meant to take the user to a designated section on the page. The first link did not function while the other two worked as intended.

## User-Interface accessability solutions

To fix the broken link the html file was examined and it was noticed that the two working links had both "id" and "class" identifiers, the first link only had a "class." Once an "id" was given to the first link it functioned properly. 

## Code Accessability problems

The CSS code has style sections for each individual "id" and "class" even when such identifiers have the same styling. Even though the webpage displays properly it is bad practice to have redundant code. 

## Code Accessability solutions

The CSS code numerous repetitive style elements. In order to shorten the code and make it more accessbile the elements that had the same styling were able to be listed together, separated by commas, and followed by the styling to be used for all. The elements were able to be grouped in threes which allowed for the CSS to be shortened up quite a bit. 

## Credits

The source code for this project is from our Rutgers Coding Bootcamp repository on Github: https://github.com/RutgersCodingBootcamp/RUT-SOM-FSF-FT-10-2020-U-C
