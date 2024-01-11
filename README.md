# Progressive-Web-Applications-PWA-Challenge-Text-Editor

# Task 
task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

# User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

# Acceptance Criteria
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application


# Mock up 
![image](https://github.com/Joeokivie/Text-editor/assets/138530272/783722d9-0660-4f5d-86c4-3e79e55a598c)

# Screenshot
<img width="1498" alt="Screenshot 2024-01-11 at 12 20 20 PM" src="https://github.com/Joeokivie/Text-editor/assets/138530272/f954ebf7-1dc1-4fa2-b0ce-8ce3bb6fef2e">

# Built with
JavaScript
Node.js
Express
Concurrently
idb
Webpack
Workbox

# Usage 
The Progressive Web Applications (PWA) Text Editor is available to users through their browser. Clicking the Install option within the application allows users to install the program locally on their computer.

# Link
https://enigmatic-anchorage-52034-687f3412666f.herokuapp.com/

# github repo
[
](https://github.com/Joeokivie/Text-editor)https://github.com/Joeokivie/Text-editor
# license
MIT
