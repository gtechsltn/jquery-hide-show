# jQuery Hide / Show

> Inserts an accessible buttons/links to hide and show sections of content.


## Usage

To get started you can either:

 - Clone the repo: `git clone https://github.com/nomensa/jquery.hide-show.git`
 - Or install with Bower: `bower install jquery.hide-show`

Then it's just a case of including the following scripts on your page, best at the bottom:

```html
  <script src="//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
  <script src="jquery.hideShow.min.js"></script>
```


## Options & Defaults

### hiddenClass

Type: `string`
Default: 'hidden'
Description: The class which is added to the content when it is hidden

### visibleClass

Type: `string`
Default: 'visible'
Descritpion: The class which is added to the content when it is visible

### buttonClass

Type: `string`
Default: 'js-hide-show-btn'
Description: The class which is added to the button for styling purposes

### buttonId

Type: `string`
Default: 'btn-control-'
Description: The ID used to target the button

### buttonExpandedClass

Type: `string`
Default: 'js-hide-show-btn--expanded'
Description: The class name applied to the button when element is expanded

### speed

Type: `string` or `number`
Default: 'slow'
Description: Takes the same value as the duration option for jQuery's slideUp and slideDown functions

### showText

Type: `string`
Default: 'Show Content'
Description: The text for the button that shows the content

### hideText

Type: `string`
Default: 'Hide Content'
Description: The text for the button that hides the content

### state
Type: `string`
Default: 'shown'
Description: Sets whether the element is hidden or shown by default, options are 'hidden' and 'shown'

### containerId

Type: `string`
Default: 'content'
Description: The id for the element to be hidden/shown

### containerClass

Type: `string`
Default: 'js-hide-show-content'
Description: The class for the element to be hidden/shown

### wrapClass

Type: `string`
Default: 'content-wrap'
Description: The class for the content wrapper

## Development

This plugin requires:

[node.js](http://nodejs.org/) `~0.10.x`
[Grunt](http://gruntjs.com/) `~0.4.0`
[jQuery](http://jquery.com) `~v1.9.x`

### Node
First time setup of this plugin will require the node packages to be installed. On Windows use the command prompt with Ruby or on a Mac use terminal, install the global node.js packages:

```bash
$npm install
```

### Grunt
If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to install and use Grunt.

You will need to install the Grunt CLI (command line interface):

```bash
$ npm install -g grunt-cli
# => if you have used grunt before you probably have this (this can be run from any directory)
```

Next install the plugin's node packages:

```bash
$ npm install
```

### Watcher

Running grunt (with watcher) will watch for any changes and recompile - best used during development:

```bash
$ grunt
```

## Supported Browsers
* Firefox 23.0.1
* Google Chrome 29.0.1547.66 m
* Internet Explorer 7, 8, 9, 10 & 11
* Opera 12.16
* Safari 5.1.7


## Release history

 - 0.1.1 Improved button to allow for better customisation
 - 0.1.0 Tagged stable version for release

Copyright &copy; 2014 [@nomensa](http://nomensa.com)

Licensed under [MIT](http://opensource.org/licenses/mit-license.php)