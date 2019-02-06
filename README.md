# staticSkeleton
Simple Brunch application skeleton with modules already included for pug, scss, live reload, etc.; a preset file tree; a Makefile for shortlist of CLI commands; and a dynamic starter layout.

This site is built with Brunch.js, Pug, SCSS, and JQuery. Follow these
steps to get it running on your own computer:

## Installation

Clone this repo

## Getting started

* Install (if you don't have them):
    * [Node.js](http://nodejs.org): `brew install node` on OS X
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * Brunch plugins and app dependencies: `make`

* Run:
    * `make server` — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).

* Learn:
    * `public/` dir is fully auto-generated and served by HTTP server.  Write your code in `app/` dir. To create the `publi/` dir, type `make build`.
    * Place static files you want to be copied from `app/assets/` to `public/`.
    * [Brunch site](http://brunch.io), [Getting started guide](https://github.com/brunch/brunch-guide#readme)

* You should see:
![](images/readme.png ?raw=true)


## ES-next

To use proposed JS features not included into ES6, do this:

* `npm install --save-dev babel-preset-stage-0`
* in `brunch-config.js`, add the preset: `presets: ['latest', 'stage-0']`
