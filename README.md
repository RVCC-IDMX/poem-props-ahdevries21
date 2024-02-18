# IDMX 11ty Sass Starter

The set of development scripts in this starter is configured to watch and compile a simple Sass structure using 11ty.

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifiying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

## Installation

**`npm install`**

>Run this command once to install the needed node modules.

## Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and served at the url localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS.

Use this as the "Publish command" if needed by hosting services such as Netlify.

## Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small>

## Website Content
The poem is called [_The Night_](https://englishverse.com/poems/night_blake) by William Blake. He is an English 18th Century Romantic Poet, and is consider one of the greatest artistic and literary genius of his time. His poem is about the sun setting, saying goodbye to its light and bring in the night, which takes over. But others have interuptteded it to be about life itself.

The picture was taken by Max Saeling on Upsplash [Click here!](https://unsplash.com/photos/trees-under-starry-sky-ef0sXQtnCYU)

![image](https://github.com/RVCC-IDMX/poem-props-ahdevries21/assets/145778459/cb12dbc9-8a21-444f-b1d5-3292076a82cd)
