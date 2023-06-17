# Create-Extension-for-browser
Sample Example For creating Extension

1) Create a new directory for your extension and navigate to it in the terminal.
2) Create a new file named manifest.json and add the following content to it. This manifest file specifies the basic information about your extension and sets up a browser action that will display a popup when clicked. Make sure to place an icon.png file in the same directory.
3) Create a new file named popup.html and add the following content to it. This HTML file sets up the structure of the popup and includes the jQuery library along with a popup.js file.
4) Create a new file named popup.js and add the following content to it.This JavaScript file uses jQuery to handle the click event of the button with the ID myButton and updates the text of the paragraph with the ID message.
5) Download the jQuery library from the official website (https://jquery.com/download/) and save it as jquery.js in the same directory as the other files.
6) Open your preferred browser (e.g., Chrome) and go to the extensions page.
7) Enable the "Developer mode" if it's not already enabled.
8) Click on "Load unpacked" or "Load unpacked extension" (depending on the browser) and select the directory where your extension files are located. The extension should now be installed and displayed as a button in the browser's toolbar.
9)Click on the extension button to open the popup, and when you click the "Click me!" button, the message should appear below it.
