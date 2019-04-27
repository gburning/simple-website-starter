# Simple Static Website Starter

This is a very simple static site generator. It makes for a good starting point for quickly building small, simple and performant websites.

## Tools

Part of the point of this project is to keep things as simple and close to the metal as possible. But some helpful tooling is included to make your life a little easier. 

Most notably, we use [Parcel](https://parceljs.org/) to build the project. This enables the use of PostHTML (extends and includes) and PostCSS (by default only to use autoprefixer). We also get a simple dev server with Hot Module Reload by default. Neat!

* To start the dev server and continually build: `npm run start`
* To build for production: `npm run build`

Another thing to note is the inclusion of `generic.css` which holds some sane defaults/resets of styling. Check it out!

## Todo
* [ ] Figure out deploy