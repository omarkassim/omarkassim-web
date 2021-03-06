# OMARKassim.com

[![Netlify Status](https://api.netlify.com/api/v1/badges/527f1bcc-6431-416f-b288-66515d3c0760/deploy-status)](https://app.netlify.com/sites/omarkassim/deploys)

This is the source for my personal site, [OMARKassim.com](https://omarkassim.com).

I was inspired by Max Boeck's personal site, [mxb.dev](https://mxb.dev) and [forked his site](https://github.com/maxboeck/mxb) as a starting point. Much props to him for a beautiful clean, layout.

This site is built with [Eleventy](https://www.11ty.io).

## License
[MIT License](/LICENSE). All content is copyright Omar Kassim.

## Features

* Static Files
* BEM-flavoured Sass (w/ Embedded Critical CSS)
* Vanilla JS (ES6 / Babel)
* System Fonts & FOUT
* Offline Support w/ Service Worker
* Focus on Speed and Accessibility

## Installation

Eleventy is a static site generator based on Javascript, which means you will need node and npm (or yarn) to run it.

Inside the project root, run `npm install` to install all dependencies.

Run `npm start` to get your development build up and running!

## Getting Started

The local development environment uses gulp to process various stuff for the site. 
The most important commands can be run as npm scripts:

`npm start`: make a development build and serve the site through browsersync  
`npm run build`: make a production build  
`npm run serve`: serve the current build `dist` directory  
`npm run debug`: start Eleventy in debug mode and serve the site

## Additional Bits

Added [`npm-force-resolutions`](https://www.npmjs.com/package/npm-force-resolutions) to fix npm package vulnerabilities that [remained open after Eleventy's v0.11.0 release](https://github.com/11ty/eleventy/issues/1164) 
