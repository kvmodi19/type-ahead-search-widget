#Detailed requirements
## Search icon (magnifying glass)
	should not be interactive
## Reset button
	should be shown if one or more characters entered in the search input field
	should clear input field value on click, touch or ‘enter’ press
	should set focus on the input field after clearing input field value if the
input field was not in focus when the reset button has been pressed
## Results drop down
	should be shown if one or more characters entered in the search input field
	should contain a list of phrases that include the search query string.
	Query string inside each phrase should be highlighted in bold
	should be scrollable if more than 5 matching results have been found.
	Browser-native inertia scroll should work on mobile
	should be updated on every query string change
	should hides if shown and the user pressed outside the search widget
## Keyboard navigation
	the user should be able to navigate back and force between the input field, reset button and drop down using tab or shift+tab keys
	the user should be able to navigate through drop-down items using up and down arrows
### when user press ‘ESC’ key
	if the focus is on the reset button, drop-down menu or on one of its items, the focus should be set on the input field
	if the focus is on the input field, input field value should be cleared