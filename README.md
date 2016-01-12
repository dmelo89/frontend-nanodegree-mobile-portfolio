
## Overview

For this project I used [Web Starter Kit](https://developers.google.com/web/starter-kit) to help me with the main Gulp tasks to build the project and do all the steps for optimizing page performance (minification and etcetera). 


## Quickstart

Clone this repository and build on what is included in the `app` directory.

You'll need to have NodeJs in your enviroment.

You'll have to use `npm install` to install dependencies

Build the repository using the `gulp` command. Production-ready files will be in the "dist" folder.

## Making changes to the project

Use the `app` directory for editing any code, and then use `gulp serve:dist` command to serve these files with optimized code.

## Changes I made in Pizza .js

* Removed the "String.prototype.capitalize" and "capitalize" function and replaced it for a CSS style rule instead;
* Removed the moving pizzas background because even with optimization it still looks ugly and does not add any feature in an User Experience point of view;
* Cut by half the number of pizzas generated by the script;
* Changed querySelector to getElementById where possible;
* Changed querySelectorAll to getElementsByClassName where possible;
* Optimized the changePizzaSizes function comments in file descript what I did;
* Removed (by commenting them) scripts that measured performance when the program builds as they are not useful for the user only for the developer.

## Other changes I made to get better performance

* Optimized all images from the portfolio and pizza website for faster rendering without losing quality;
* Optimized navigation buttons in the 'pizza' page for better DOM building ("<form>" and "<input>" to "<a>" tags);
* Used the apache-server-configs's .htaccess to activate module that makes performance better (mod_deflate);
* Optimized CSS rendering to get a 98/100 score in PageSpeed for mobile;
* Optimized Images in home + optimized CSS rendering 'above-the-fold' to get a 99/100 score in PageSpeed for desktop;
* Removed performance test JavaScript that is not meant to be in the production enviroment.