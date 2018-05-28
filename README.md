# [Polling Application - NOS]

# Prerequisites
You should have node and npm installed in your system.

# Download and Installation

To begin using this app, follow steps to get started:
* Clone the repo
* Run `npm install`
* After this run `gulp dev` which will launch the application in your local


## Advanced Usage

After installation, run `npm install` and then run `gulp dev` which will open up a preview of the application in your default browser, watch for changes to core application files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp sass` compiles SCSS files into CSS
- `gulp minify-css` minifies the compiled CSS file
- `gulp minify-js` minifies the themes JS file
- `gulp copy` copies dependencies from node_modules to the vendor directory
