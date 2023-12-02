# Project-Pickup-lines
This is a simple web page that displays a random pickup line when a button is clicked.
- HTML: Displays pickup lines, a button to generate them, and a copyright notice.
 div with id pickup-line: Displays pickup lines.
 button with id button: User clicks to generate new pickup line.
 div with class copyright: Displays copyright notice.

- CSS: Styles the page and its elements.
 Styles the page, including background, text alignment, and fonts.
 #pickup-line and #button selectors style the pickup line and button.
 .copyright selector styles the copyright notice.

- JavaScript: Generates a random pickup line when the button is clicked.
 impressCrush function: Generates a random pickup line when button is clicked.
 pickupLines variable: Contains all possible pickup lines.
 pickupLine variable: Stores a random pickup line from pickupLines.
 document.getElementById("pickup-line").innerText = pickupLine;: Updates the pickup-line div with new pickup line.

