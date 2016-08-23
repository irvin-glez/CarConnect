# Find and Fix the Bugs

This is an Express TODO web application, but it has numerous bugs. The QA department has found the following bugs and you need to fix them.

Your job is to pair up with another student and reproduce and fix each of the bugs. Time is money so get to fixin'!!!

## Steps
1. pair up
2. clone this repository
3. reproduce and fix each bug listed below

## List of Bugs
1. The quick toggle feature on the TODOs _INDEX_ page does not work (gives a 404 error).
2. The _EDIT_ page has a `Back` button that should take the user to the _SHOW_ page but it takes the user to the _INDEX_ page. Make it navigate to the _SHOW_ page.
3. The Navbar always displays the "Logout" link. It should only display when the user is already logged in.
4. The _NEW_ page does not load. When the user clicks on the "New" button from the TODOs _INDEX_ page a 404 error is returned.
5. When the user goes to the TODO _EDIT_ page and tries to save a TODO with the completed checkbox _not checked_, an error occurs with the message "User validation failed."
