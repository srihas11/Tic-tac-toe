##Tic-tac-toe

### (13/02/23)

#### Summary of what I've learnt from this game.

- [x] Basically,Index.html is like a homepage for some website, for example, if we take Google.com or some other website you could see the logo at the center, It is like a base, but you access multiple other websites from it.

- [x] If we split the code into multiple files, there would be no problem with the html file, we would just do script src ="script-1.js" once and if you have 2 or more you just have to do script src ="script-2 or 3." and </script> at the end.

 - [x] Certain were used functions to create logic. 

 * handleCellClick - In this tic-tac-toe code, to see if the cell was already clicked and played and if not, to continue the game. To handle both of them they used this funtion.

 * handleCellPlayed -  When we play tic-tac-toe online, when ever you clicked in the boxes you used to get an "O" or a "X".   For that, handleCellPlayed is used to the same, Update the game when clicked and update & show it on user's interface.

 * handleResult Validation - The result validation is the core of the tic tac toe game. Here only we will check whether the game will end with a win or a draw.

 * handlePlayerChange - This will change the current player and update the game status. It will change the current player to next and assigns some value to next player.

 * handleRestartGame - This will set all the game back into default and a new game begins.

 - [x] The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data in the document, in this over the viewport (the user's visible area of a web page), through the <meta> tag. 

 - [x] If there was no CSS, we could still make the game, but it will look like a boring and ugly website. CSS makes it look more attractive and beautiful.

 - [x] If there was no Javascript there would be no logic at all. We wouldn't even be able click on something and play the game.

 - [x] For storing any value, we need a variable, so first, we will declare a var variable and then assign some value to the variable.

 - Let variable introduces a special feature that does not allow re-declaration of variables, if you remember, re-declaration was a problem in var variable but let variable solve this problem.

 - The const declaration creates block-scoped constants, much like variables declared using the let keyword.

 - [x] For indicating that no statement will be executed, even if JavaScript syntax requires one.

 - [x] In this tic-tac-toe code, they used Array object to store multiple values in a single variable. It stores a fixed-size sequential collection of elements of the same type.