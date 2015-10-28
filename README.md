# Web Scaffold
My current best web scaffold (angular focused)

## Quick start
Modify package.json to match your project information and run `npm install`  This will also run `bower install`

Build your html in `app/index.html`  

Place your main application js in `app/scripts/app.js`

## Testing
run `npm start` to build and launch your web app.  Changes to the code will reload your browser window too!

## Build for production
run `grunt build` and your output will appear in the `dist` folder ready for production.

## What it does for you

1. Minify javascript
1. Compile less to css
1. Minify css
1. Minify images
1. replace `@@timestamp` with current timestamp in all source files (for cache busting)
1. remove javascript console logging
1. live reload on source changes
