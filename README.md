# Frontend Automation
Automate frontend using task runner gulp

Prerequisites:
- Knowledge of Node.js, Gulp Js
- Pre Installed Node and Gulp globally on local system

Installation Steps:
- Download repositiory to your system. Extract it.
- Copy and paste files into the theme directory of your project.
- Open "Node Terminal", Go to your project theme directory.
- To make this work type following commands into your "Node Terminal".
	1) Type "npm install" into terminal
		 As "package.json" is already present in project theme directory, Node will install all the dependencies required for automation
	2) Next step is type command "npm install gulp-cli -g" and "npm install gulp -D"
		 This will install gulp globally into system as well as node will treat as a dependency for your project.

Now that installation is completed. Open "gulpfile.js". Do the necessity changes like changes folder path, arrangement of task as per the need.

List of tasks added into gulpfile.js are:
- gulp : http://gulpjs.com/
- gulp-sass : https://www.npmjs.com/package/gulp-sass
- gulp-sourcemaps : https://www.npmjs.com/package/gulp-sourcemaps
- gulp-watch : https://www.npmjs.com/package/gulp-watch
- gulp-autoprefixer : https://www.npmjs.com/package/gulp-autoprefixer 
  - check out the prefixer available option here: https://github.com/postcss/autoprefixer#options
- gulp-scss-lint : https://www.npmjs.com/package/gulp-scss-lint 
  - You also need to install scss lint for that use command "gem install scss_lint"  
- gulp-csscomb : https://www.npmjs.com/package/gulp-csscomb
  - Check out the csscomb available options here: https://github.com/csscomb/sublime-csscomb/blob/master/node_modules/csscomb/doc/options.md
  - Download csscomb.json which is already sorted as per standard and replace it in your node_modules/csscomb/config
- gulp-imagemin : https://www.npmjs.com/package/gulp-imagemin
  - Check out the imagemin available options here: https://github.com/sindresorhus/gulp-imagemin
- gulp-jshint : https://www.npmjs.com/package/gulp-jslint
  - You need to install: npm install --save-dev jshint-stylish
- gulp-jsbeautifier : https://www.npmjs.com/package/gulp-jsbeautifier
  - Check out the JSPrettify available options here: https://github.com/beautify-web/js-beautify
- gulp-uglify : https://www.npmjs.com/package/gulp-uglify
  - Check out the uglifyjs available options here: https://www.npmjs.com/package/gulp-uglify  
- gulp-uglifycss : https://www.npmjs.com/package/gulp-uglifycss
  - Check out the uglifycss available options here: https://github.com/fmarcia/UglifyCSS  
- browser-sync : https://browsersync.io/docs/gulp
- gulp-livereload : https://www.npmjs.com/package/gulp-livereload 
  - Check out the livereload available options here: https://scotch.io/tutorials/a-quick-guide-to-using-livereload-with-gulp 

Once this is done, you are ready to start automating frontend. 
In "node terminal", go to your project theme directory and type command as per your task (for example: To compile sass file need to run command like "gulp sass-watch"). As per this you can run other commands also as per your requirement.
