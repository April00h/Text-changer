# Text-changer
# Social-Networking-with-API-


## Table of Contents
- [Summary](#summary)
- [Features ](#features)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Contributing](#contributing)
- [Questions](#questions)
- [License](#license)

### Summary 

This is a PWA text editor with JavaScript syntax highlighting, enabling users to take notes, write code snippets, and save them locally in their browsers via IndexedDB. It includes service worker integration for offline use and follows PWA best practices for a smooth user experience.



## User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use


## Acceptance Criteria

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

## Installation 

Clone the repository to your local machine:

Copy code

git clone <[repository-url](https://github.com/April00h/Text-changer.git)

cd text-editor
Install dependencies using npm

Copy code
npm install

Build the project:

Copy code
npm run build

Copy code
npm start



## Contributors
[April Hunt](https://github.com/April00h)


## Questions
Please reach out with any questions or concerns: [E-mail](mailto:), [E-mail](mailto:aprilhunt00.ah@gmail.com)

## License 
This project is licensed under the MIT License.
