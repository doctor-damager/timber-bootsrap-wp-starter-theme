# Timber / Bootsrap / Wordpress Starter Theme

This project adds Bootstrap 4 and other dev dependencies to the official Timber Starter Theme to create an automated workflow for fast but clean developing of Wordpress Themes.

## Installation
1. Clone git repo to _wordpress_root_/wp-content/themes/
2. Rename the folder to your theme name (optional)
3. Install package.json (`yarn install` or `npm install`)
4. Install Timber Plugin (and optional Advanced Custom Fields Plugin - works good together)
5. Activate your Theme

Next Steps: 
+ Create a main menu if not done already
+ run `$ yarn run watch` and start customizing your styles/js (see Task Automation)

## Task Automation

The Task Automation is taken from / inspired by https://github.com/them-es/themes-starter-bootstrap
This includes: 
+ gulp
+ weppack
+ browsersync

Same instruction as in the link above:
Sass files will be compiled if changed, vendor prefixes will be added automatically and the CSS will be minified. JS source files will be bundled and minified.

+ Prerequisites: Node.js (NPM) needs to be installed on your system
+ Open the Project directory / in Terminal and install the required Node.js dependencies: gulp, webpack, Sass-Compiler, Autoprefixer, etc.
+ `$ yarn install`
+ Run the watch script
+ `$ yarn run watch`
+ Modify /assets/main.scss and /assets/main.js