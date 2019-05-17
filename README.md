# Volvo frontend task - Java VIII

Volvo frontend task with custom grid and gulp task runner for compiling scss to css.

## Gulpfile configuration
In gulpfile.js is created task for compiling scss to css.
Scss file is compiling from:
```
src/scss/styles.scss
```
to
```
src/css/styles.css
```

## How to work with this project
if you want to see my grid you need to go into project root directory and in terminal write this commands.

Install packages:
```
npm install
```

Compile scss to css:
```
npm run gulp-sass
```

After this two commands simply open index.html in browser.




## Create your own layout
If you want create elements using my grid you need to wrap all the div HTML elements by div element with class "wrapper".
HTML div elements inside must contain special classes.

For proper displaying element lower than 576px use this:
col-xs- with number of columns (for example: col-xs-12)

For proper displaying element between screen sizes from 576px to 767px use this:
col-sm- with number of columns (for example: col-sm-6)

For proper displaying element between screen sizes from 768px to 991px use this:
col-md- with number of columns (for example: col-md-3)

For proper displaying element between screen sizes from 992px to 1199px use this:
col-lg- with number of columns (for example: col-lg-2)

For proper displaying element greater than 1200px use this:
col-xl- with number of columns (for example: col-xl-1)