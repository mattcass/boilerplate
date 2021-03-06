Boilerplate for your projects made with [Gulp](http://gulpjs.com/), [Sass](http://sass-lang.com/), [jQuery](http://jquery.com//)

Inspiration & Heavy lifting by [zerosixthree](http://zerosixthree.se/).

![alt tag](images/boilerplate.png)

Requirements
-------------
[NodeJS](http://nodejs.org/) and [Gulp](http://gulpjs.com/).

Installing
-------------
Step 1. Install [NodeJS](http://nodejs.org/download/)

Step 2. Install [Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#getting-started)
```shell
npm install --global gulp
```

Step 3. Install all the npm dependencies you need for Gulp
```shell
cd path/to/project
npm install
```

Step 4. Done!

Gulp tasks
-------------
There is currently one Gulp task; `gulp`

`gulp` is the default task and will concatenate and minify all Javascript files in to
`dist/js/script.min.js`. The task will also concatenate all Sass files into
`dist/css/style.css` and run autoprefixer on the outputted CSS file to
ensure all the correct vendor prefixes are included. `gulp` uses the
`gulp watch` task, so it automatically runs every time a JS/Sass file changes.

Using `gulp-plubmer` and `beepbeep` the terminal will beep to alert you anytime
there is a JavaScript or SASS error and log the error in the console.

There is also a liverelaod script built in that automatically reloads your
browser any time there is a change to an html file, or the css and js `dist` files.

Folder structure
-------------
The development will be done in `source/js/` and `source/scss/` which then will
be compiled/concatinated/minified into `dist/js` and `dist/css` accordingly.
