# html skeleton
## html skeleton is just a pre-build webapp skeleton (you don't say !)
###### Start an app, from scratch, with a clean markup !
###### Feel free to use / customize it / suggest some improvements

## HTML files

The main file is index.html, it includes a basic HTML5 webapp skeleton, it contains the head with metas, body with some basic markup (header, main, section, footer etc), and CSS/JS files includes

It also includes some 4xx and 5xx errors pages

## CSS files

The CSS folder includes several CSS files

It contains a file for each parts of the template (header, common, main, footer, responsive and variables) which are imported into the main LESS file, and finally compiled into the style.min.css file

There is also the normalize.css file in the vendor folder (v7.0.0)

## JS files

There is just a main.js file and the main.min.js file and the jquery-3.2.1.min.js in the vendor folder

## .htaccess

This file contains the most common 4xx and 5xx erros redirections, some compressions / caching / proxy stuffs and the [6G Firewall](https://perishablepress.com/6g/)

Please note that you should rename this file into .htaccess with a dot a the beginning

## other files

There is just a sample PNG favicon in the favicon file. Note that you should generate your own favicon with some service like [favicon-generator](https://www.favicon-generator.org/)

## SPECS

- For LESS : Any LESS stuff so the style.less could minify and compile into the style.min.css (IDE plugin or some task runner like Gulp or Grunt)
- For the JS : Any minifier stuff so the main.js could minify correctly into the main.min.js (same as above)

## Coming Soon

- The SASS / SCSS version
- The vanilla CSS version
