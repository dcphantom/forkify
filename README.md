# Forkify
Forkify is a vanilla Javascript application that interacts with the Forkify API to fetch and display food recipe data.

## Refactored _generateMarkup function in paginationView.js
I refactored the code for the pagination buttons HTML template strings into a new function called _generateMarkupButton to improve the DRY-ness of the _generateMarkup function. Now for each current page condition in the search results, the _generateMarkupButton function dynamically creates and returns a template string containing the HTML for the desired button type (prev/next) and goto page number.
