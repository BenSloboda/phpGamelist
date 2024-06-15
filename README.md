# phpGamelist
A PHP application to build up a text file of games I own

This application has a few pieces:

gamelist.html
-Front page with a little text input box that allows you to start typing a game name and the autocomplete will show if the game exists in the list (and what system it is on).

awesomeplete.js
-Lea Verou's Awesomplete Javascript local library

awesomeplete.css
-Awesomplete associated CSS

gamelist.txt
-A text file containing all games owned in a csv in no particular order. 
-Uses `(tick mark) at the beginning and end, as well as let text= for some reason.

welcome.php
-This was a very rudimentary attempt at providing some security.  If you are able to guess the password from the users.txt file (which is not included here).
-If password correct, loads the phpTest.html page, which allows editing the gamelist.txt file

phpTest.html
-Front page with a little text input box that allows you to start typing a game name and the autocomplete will show if the game exists in the list (and what system it is on).

info.php
-This is the actual php that will allow appending to the gamelist.txt file
