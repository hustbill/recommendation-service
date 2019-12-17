# Search Bar using HTML, CSS and JavaScript
[Reference](https://www.geeksforgeeks.org/search-bar-using-html-css-and-javascript/)

Every website needs a search bar through which a user can search the content of their concern on that page. A basic search bar can be made using HTML, CSS, and JavaScript only. Advance searching algorithms look for many things like related content and then shows the results. The one that we are going to make will look for substrings in a string.


## JavaScript

In the HTML code of search bar, we gave the input an id=”searchbar” and onkeyup we called, the function “search_animal”. onkeyup calls the function every time a key is Released on the keyboard.
We first get our input using getElementById. Make sure to convert it to lower case to avoid case sensitivity while searching. An array of documents is stored in x. This contains every list that has id=”animals”. After that a loop is run to check if innerHTML of every document includes the input substring if it doesn’t, the display property is set to ‘None’ so that it is invisible on the front end.
