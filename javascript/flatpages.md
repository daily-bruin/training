# The Flatpage Template
At the Daily Bruin, we make a lot of static, front-end content we call _flatpages_. Since we do this a lot, we've recently made a [template](https://github.com/daily-bruin/flatpage-template) (**mandatory**) that organizes and standardizes the tooling of this process. The main component of this template is a tool called Gulp.

## Gulp
Gulp what's called a task runner: it automates common development tasks for you and runs them automatically. What can it do? Compile Nunjucks and Sass files, compress images, [minify](https://blog.stackpath.com/glossary/minification/) (**mandatory**) files, and a whole lot of other very useful things in the development workflow.

### Installation
To install Gulp, you'll need to first install Node.

Mac:
```shell
brew install node
```

Windows:
```shell
choco install nodejs
```

After installing Node, the command for installing Gulp is the same for both systems:
```shell
npm install gulp-cli -g
```

### The Gulpfile
The main idea of Gulp is that you specify tasks for it to perform through a file called a Gulpfile. A Gulpfile is written in JavaScript (which we won't cover until next week!) but you can take advantage of a Gulpfile that we've already written right now. There are two commands you need to know: `gulp` and `gulp build`. `gulp` sets up your project in a development environment, while `gulp build` readies your project for production.

## Technologies Used
The next couple of sections cover technologies that are built in to the flatpage template. Pay attention to them because they're cool.

## TL;DR
Use the [flatpage template](https://github.com/daily-bruin/flatpage-template). Learn the technologies it uses!
