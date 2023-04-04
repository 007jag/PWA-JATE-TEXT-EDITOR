# PWA-JATE-TEXT-EDITOR
[link to heroku deployed app](https://jags-text-editor.herokuapp.com/)

## Description

J.A.T.E is an offline, browser-based Progressive Web Application (PWA) that may be installed locally on your computer. This application employs a number of data persistence strategies to ensure that it runs regardless of the browser's supported functions. The IndexedDB database and the idb package are used by J.A.T.E. 

## Table of Contents
[Description](#description)
-[Table of Contents](#table-of-contents)
-[Installation](#installation)
-[License](#license)
-[Technologies](#technologies)
-[Questions](#questions)

## Usage
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

## Installation
to run this application on your computer clone this repository and then go to the directory
open your terminal and run npm install to get your dependencies. finally you can run the application using npm start

1. Pull down and/or branch this repository
2. Run ```npm i``` to install all dependencies
3. Invoke application with ```npm run start```

## License
[MIT License](./LICENSE)

Copyright (c) 2023 Jagmit Cheema

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Technologies 
- JavaScript
- Webpack+Workbox
- NodeJS
- IndexedDB
- Babel
- Concurrently
- Express
- Mini-CSS-Extract Plugin


## Tests
No tests were run to complete this CMS.

## Questions
if you have any questions email me at jagmitsingh2003@gmail.com

- - -
© 2023 Just Another Text Editor (J.A.T.E) PWA by Jagmit Cheema 