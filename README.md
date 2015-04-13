# <img src="https://github.com/derek-skinner/Inflame/blob/master/favicons.ico/Inflame_Logo.png" alt="Inflame" title="Inflame" width="400">

This project is meant to be used as a starting boilerplate to your web projects. Includes folder structures, Favicons. task automation, grunt plugins, and more.

[![Dependency Status](https://david-dm.org/derek-skinner/Inflame.svg)](https://david-dm.org/derek-skinner/Inflame)
[![devDependency Status](https://david-dm.org/derek-skinner/Inflame/dev-status.svg)](https://david-dm.org/derek-skinner/Inflame#info=devDependencies)
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

## Dependencies

If you don't already have the following installed, you will need to install these first:

Majors:

* Node.js
* Ruby

Secondaries:

* Node: npm
* Ruby: Sass 3.3.x

After you've set this stuff up please run

	$ npm install -g grunt-cli bower

This installs the Grunt command line tools and bower.
Then CD into your directory of choice and run:

	$ npm install

This will install all the things you need for running the grunt-tasks
automatically. Then install the Bower components using:

	$ bower install

That command will create a folder `Bower_Components` which holds all vendor dependencies
managed by Bower that are listed in the `bower.json` file.


### Troubleshooting

If running the install does not work, please try running it with
admin-rights:

	$ sudo npm install -g grunt-cli


## Browser support

* Chrome
* Firefox 4+
* Internet Explorer 8+
* Opera 12+
* Safari 5+


## Contribute

Feel free to contribute and help this project grow! Any support and/or feedback is always welcome.


## CSS

We are currently working with [Sass](http://sass-lang.com/) (in its dialect
SCSS) and do not use CSS directly. Please do not edit the CSS-files in any case
but search the corresponding `.scss` file and edit it accordingly. If you are
not familiar with SCSS you can write pure CSS which is actually valid SCSS.

However all `.scss`-files are compiled into one file called `main.css` in the
`css`-folder.

You can find more information about the installation process of Sass and the
usage of SCSS in the [Sass Tutorial](http://sass-lang.com/tutorial.html).


## JS

Currently in use is jQuery, Modernizr and RequireJS.

Please use JSHint for your JavaScript before you commit. You can use the
Grunt-task `jshint` for this. You can also just run `grunt watch`.


## Creating a Build

Please use [Grunt.js](https://github.com/gruntjs/grunt) for building a
production-state of a website. The `Gruntfile.js` has tasks for concatenating
and minifing CSS and JavaScript.

Additional information on this project is stored in `package.json`.


## Development

This project is developed and maintained by
[Derek Skinner](http://derekskinner.tv/),



## Credits

Credits will be added here as needed.


## License

Please be aware of the licenses of each component that is used in this project.
Everything else that has been developed by the contributions to this project is
under [MIT License](LICENSE.md).
