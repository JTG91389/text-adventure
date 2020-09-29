# text-adventure
A text based adventure game built for the browser

# Text-Adventure(react)
This project is our react/webpack/babel/sass build, built off of https://github.com/ReactJSResources/react-webpack-babel

In order to run on node 12.* you'll need to go to the follow node_modules path (text-adventure/node_modules/@babel/helper-compilation-targets/package.json) and change ln 47, '"exports": false,' to this code block

'
"exports": {
    ".": "./lib/index.js"
  },
'

This is due to a current babel conflict witht he latest version of stable node (12.18.*)

To run the react app, inside the text-adventure directory run the following
npm install
npm run dev 

this will start up our webpack local dev server with the webpack dashboard in CLI

# Vanilla-Text-Adventure
This is a vanilla JS version of test adventure, we'll be running this to quickly pilot pieces of code and test out UI, while we figure out how we're going to do this thing. A POC if you will of the game before we move it into production stable boilerplate using react. 
