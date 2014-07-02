undef-example
=============

Showing off undef to build require.js modules, the simplest it gets.

Set it up
=========

In order to run this app simply follow those steps:
1) Clone this repo
2) `cd into/the/project/repo`
3) `npm install` to install all the (dev) dependencies into the node_modules folder of the app
4) `npm run build` to let undef do it's job and build all the files into one file inside the `dist` folder 

What do you get?
================

In short: 
undef creates one file out of multiple AMD modules, this file can now be minified and deployed.
All require.js dependencies are completely removed and only the pure code is left.
This enables nice development using require.js and provides a production code without the
niceties of require.js that are nice to have during development.

For more info see http://www.uxebu.com/blog/2014/07/02/remove-amd-artifacts-deployment
