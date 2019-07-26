# Bootstrap 4 NPM Installation Guide (1.0.3)
A readme.md only repo to keep the specific steps needed to start using a fresh Bootstrap 4 install.

## Dependencies
You'll need the following software on your local machine to follow this guide:
 * Node.js
 * NPM (Comes with Node.js)
 * VS Code (or a similar IDE)

## Installation Steps

1. Create a local project folder
1. Navigate to the folder in Terminal
	⁃ Type in "code ." (to launch VS Code (VSC) app)
1. Create a "src" folder inside your project folder
	- Inside the "src" folder, add the following folders
		- "css"
		- "js"
		- "scss"
1. Create a file inside the "src" folder called, "index.html"
1. Get a bootstrap starter template and add the code to "index.html"
1. Navigate back to the project folder, and open up the terminal pane in VSC
	⁃ Type "npm init"
	⁃ Fill out data for the package.json file npm will generate
	⁃ Type in "npm install jquery"
	⁃ Type in "npm install popper.js"
	⁃ Type in "npm install bootstrap"
	⁃ Type in "npm install prismjs"
	npm install tinycolor2
	npm install datatables.net
	npm install datatables.net-bs4
1. Type "npm install gulp browser-sync gulp-sass --save-dev"
1. Type "npm install gulp-nunjucks-render --save-dev"
1. Type "npm install gulp-data --save-dev"
1. Type "npm install gulp-json-to-sass --save-dev"
	
1. Now create a folder called "nunjucks"
	- Inside the "nunjucks" folder, create the following folder heirarchy
		- pages
		- templates
			- partials
1. Create a gulp file in the project folder called, "gulpfile.js"





npm install --save-dev gulp-autoprefixer
npm install --save-dev gulp-uglify





https://codehangar.io/concatenate-and-minify-javascript-with-gulp/

https://css-tricks.com/gulp-for-beginners/

https://stackoverflow.com/questions/38799380/how-to-create-strcuture-folder-with-gulp

npm install --save-dev gulp-shell

gulp.task('directory', function () {
	return gulp.src('*.js', {read: false})
	.pipe(shell([
		'mkdir -p  src/css src/js src/images src/fonts'
	]));
});
