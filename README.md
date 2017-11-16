# html skeleton
## html skeleton is just a pre-build webapp skeleton (you don't say !)
###### Start an app, from scratch, with a clean markup !
###### Feel free to use / customize it / suggest some improvements

## HTML files

This repo contains two html files

The main file is index.html, it includes a basic HTML5 webapp skeleton, it contains the head with metas, body with some basic markup (header, main, section, footer etc), and CSS/JS files includes

It also includes a 404.html basic file

## CSS files

The CSS folder includes several CSS files

The main file is style.less and style.min.css (which is basically the less minified and compiled file). It also contains a var.less which is already imported in the style.less

There is also the normalize.css file in the vendor folder (v7.0.0)

If you don't want to build with LESS, just replace the <link rel="stylesheet"  href="css/style.min.css"> line in the <head> by <link rel="stylesheet"  href="css/style.css">, then copy the content of the other CSS files and feel free to work on the style.css file (and to delete LESS and .min CSS stuff)

## JS files

There is just a main.js file and the main.min.js file and the jquery-3.2.1.min.js in the vendor folder

## other files

There is just a sample PNG favicon in the favicon file. Note that you should generate your own favicon with some service like [favicon-generator](https://www.favicon-generator.org/)

## SPECS

- For LESS : Any LESS stuff so the style.less could minify and compile into the style.min.css (IDE plugin or some task runner)
- For the JS : Any minifier stuff so the main.js could minify correctly into the main.min.js (same as above)

Please notre that you can work on your own workflow (SCSS, Stylus), with Gulp, Grunt etc. Feel free to fork and build your own html webapp skeleton !
