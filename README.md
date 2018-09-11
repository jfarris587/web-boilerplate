# Web Development Boilerplate

This is a web development enviornment boilerplate that uses Grunt as a task runner. Using this repo allows for a clone that gives a headstart to development with its creation of a ready to use dev/build enviornment making use of HTML/SASS/JS stack. 

The two commands for the user **grunt dev** and **grunt build** are all that is needed. Foremost, *grunt dev* runs SASS compilers, and has built in capability of running webpack+babel scripts for module based javascript. Next, *grunt build* compiles all JS and CSS to minified versions, uglifies JS, and increases the version number within settings.json. Most importantly, browserSync is used for local server, which allows for viewing on multiple devices, and links the interactions/scrolling up for all of them.

# Technology

- Grunt
- SASS
- Javascript
- Webpack
- HTML

# How to Run

Use **npm install** to install packages, and then run with **grunt dev** for development. To create the build package for deployment use **grunt build**



