For details on installing from the template or updating the template see TEMPLATE_README.md

# webpack-tailwind-starter-template
Starter Template includes Tailwind in Webpack.

## Development

## If you haven't done this in a while

Check LTS version of Node JS here (https://nodejs.org/en/) and update .tool-versions
    
    $ asdf install
    $ node --version (should return the version matching .tool-versions)

Run npm install to update to latest versions of things    


### First time

$ npm install

### Adding fonts to the project

Search "typeface-<fontname>" on npmjs.com  (eg typeface-lato for Lato)
$ npm install typeface-<fontname> --save-dev

### Starting the app

$ npm run start

### Building the app

$ npm run build   # will 'compile' app into the /docs directory.

### Hosting

The app is hosted on github pages, with the code configured to deploy the contents of the /docs directory. 

As the docs directory is auto-regenerated, for anything you want to deploy, include it in the /src directory and then rebuild the app to update it into the /docs directory.