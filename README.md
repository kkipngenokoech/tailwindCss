# tailwindCss

yes it is true that I haven't used Tailwind before, but as from today, I know Tailwind

## setup tailwind environment

to setup tailwind environment one has to install `npm i -D tailwindcss postcss autoprefixer`

### npm i -D tailwindcss postcss autoprefixer

this command will install the necessary dependencies used by Tailwind

tailwindcss is the main package for using Tailwind in a project. postcss is a tool for transforming CSS with JavaScript plugins, and autoprefixer is a PostCSS plugin that automatically adds vendor prefixes to CSS properties to ensure compatibility with different browsers.

### npx tailwindcss init -p

`npx tailwindcss init -p` - it is used to generate a tailwind.config.js file

 The init command is used to generate a default configuration file named tailwind.config.js in the current working directory. This configuration file includes the default values for all the configurable options in Tailwind.

The -p flag is used to create a PostCSS configuration file named postcss.config.js in the current working directory. This file specifies that PostCSS should use Tailwind CSS and Autoprefixer plugins to process CSS files.

## tailwindcss import

then the final step is to import tailwindcss into your project

@tailwind base;
@tailwind components;
@tailwind utilities;

this can be placed either in your app.css or your index.css
