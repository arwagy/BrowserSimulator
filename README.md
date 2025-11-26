# BrowserSimulator
A simple C++ browser simulator to visit sites ,navigate back and forward ,save browsing history .

Features :

▬Visit a new(record both time and date when a page was visited).

▬Go Back and Forward.

▬Diaplay browsing history(with maximum limit).

▬Save history to a text file.

Data Structures :

STACK for back and forward navigation ( i used stack here for the logic of the browser processes that works in that way the last page you visited is the first page you go back to (LIFO behavior)).

VECTOR for browsing history storage (dynamic array to add or remove a page easily and to store it in order.

TIME TRACKING by using time() , put_time and localtime() functions
