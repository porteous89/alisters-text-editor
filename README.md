[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# alisters-text-editor

## Description
This project is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

### User Story
```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```
### Acceptance Criteria
```md
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
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```
## Link to live Heroku deployment
https://ap-text-editor.herokuapp.com/

## Link to Repo
https://github.com/porteous89/alisters-text-editor

## Screen Shots

Running Service Worker:

<img src="assets\service-worker.png" width= 45% >

Showing Install Prompt:

<img src="assets\install-prompt.png" width= 45% >

Showing Installed Application Running:

<img src="assets\installed-app.png" width= 45% >

## Built Using
- Node.js
- Express.js
- idb
- webpack
- MongoDB
- Heroku

## License
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 
This project is licensed under the MIT license. See the [LICENSE](https://opensource.org/licenses/MIT) file for details.

## Credits

Developing Progressive Web Apps
https://codelabs.developers.google.com/dev-pwa-training/

Service Workers an Introduction
https://developers.google.com/web/fundamentals/primers/service-workers

What is Webpack
https://survivejs.com/webpack/what-is-webpack/

Getting Started with indexedDB
https://youtu.be/g4U5WRzHitM

## contribution
PLease checkout my github link for contributions -  [https://github.com/porteous89](https://github.com/porteous89).

## Questions
If you have any questions about the repo, open an issue or contact me directly at alisterporteous@hotmail.com. You can find more of my work at [https://github.com/porteous89](https://github.com/porteous89).

