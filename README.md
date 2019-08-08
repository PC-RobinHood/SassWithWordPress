# SassWithWordPress
Template for hot-reloading Sass into WordPress Projects.

# Denpendencies
NodeJS, NPM

# Steps to use
1) Insert package.json into root of wordpress plugin/theme. 
2) Install node dependencies. (npm/yarn install)
3) Run scripts (located in package.json). npm run css | yarn css (compiles css). npm run watch | yarn watch (watches for changes in scss files and compiles to css file automatically). 

# How it works
The source file (source.scss) imports files from partial and vendor folders. When scripts are run, style.css in root gets compiled.
