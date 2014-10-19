# Social Sharing [![Build Status](https://travis-ci.org/cferdinandi/social-sharing.svg)](https://travis-ci.org/cferdinandi/social-sharing)
Add social sharing links and buttons without the bloat.

[Download Social Sharing](https://github.com/cferdinandi/social-sharing/archive/master.zip) / [View the demo](http://cferdinandi.github.io/social-sharing/)

**In This Documentation**

1. [Getting Started](#getting-started)
2. [Installing with Package Managers](#installing-with-package-managers)
3. [Working with the Source Files](#working-with-the-source-files)
4. [Browser Compatibility](#browser-compatibility)
5. [How to Contribute](#how-to-contribute)
6. [License](#license)
7. [Changelog](#changelog)



## Getting Started

Compiled and production-ready code can be found in the `dist` directory. The `src` directory contains development code.

### 1. Include Social Sharing on your site.

```html
<link rel="stylesheet" href="dist/css/social-sharing.css">
```

If you're not using the [Kraken boilerplate](http://cferdinandi.github.io/kraken/), you might also need to include the button styling.

```html
<link rel="stylesheet" href="css/kraken-buttons.css">
```

Social Sharing is [built with Sass](http://sass-lang.com/) for easy customization. If you don't use Sass, that's ok. The `css` folder contains compiled vanilla CSS.

The `_config.scss` and `_mixins.scss` files are the same ones used in [Kraken](http://cferdinandi.github.io/kraken/), so you can drop the `_social-sharing.css` file right into Kraken without making any updates. Or, adjust the variables to suit your own project.

### 2. Add the markup to your HTML.

**Branded Buttons**

A few simple classes turn `button` and `a` elements into branded social media buttons.

```html
<a class="btn btn-tweet" href="#">Twitter</a>
<a class="btn btn-facebook" href="#">Facebook</a>
<a class="btn btn-google" href="#">Google+</a>
<a class="btn btn-linkedin" href="#">LinkedIn</a>
<a class="btn btn-pinterest" href="#">Pinterest</a>
<a class="btn btn-github" href="#">GitHub</a>
<a class="btn btn-vk" href="#">VK</a>
<a class="btn btn-xing" href="#">Xing</a>
<a class="btn btn-tumblr" href="#">Tumblr</a>
<a class="btn btn-reddit" href="#">Reddit</a>
```

**Sharing Links**

To include sharing links for Twitter, Facebook, Google+, LinkedIn and more, just add your URL's and titles where indicated in these snippets. Combine with the branded buttons for sharing buttons.

```html
<a target="_blank" href="https://twitter.com/intent/tweet?text=YOUR-TITLE&url=YOUR-URL&via=TWITTER-HANDLE">Tweet</a>

<a target="_blank" href="https://www.facebook.com/sharer/sharer.php?u=YOUR-URL">Share on Facebook</a>

<a target="_blank" href="https://plus.google.com/share?url=YOUR-URL">Plus on Google+</a>

<a target="_blank" href="https://www.linkedin.com/shareArticle?mini=true&url=YOUR-URL&title=YOUR-TITLE&summary=YOUR-SUMMARY&source=YOUR-URL">Share on LinkedIn</a>

<a target="_blank" href="https://pinterest.com/pin/create/button/?url=YOUR-URL&description=YOUR-DESCRIPTION&media=YOUR-IMAGE-SRC">Pin on Pinterest</a>

<a target="_blank" href="https://vk.com/share.php?url=YOUR-URL&title=YOUR-TITLE&description=YOUR-DESCRIPTION&image=YOUR-IMAGE-SRC&noparse=true">Share on VK</a>

<a target="_blank" href="https://www.xing-share.com/app/user?op=share;sc_p=xing-share;url=YOUR-URL">Share on Xing</a>

<a target="_blank" href="http://www.tumblr.com/share/link?url=YOUR-URL&description=YOUR-DESCRIPTION">Share on Tumblr</a>

<a target="_blank" href="http://www.reddit.com/submit?url=YOUR_URL&title=YOUR_TITLE">Share on Reddit</a>
```

And that's it, you're done. Nice work!



## Installing with Package Managers

You can install Social Sharing with your favorite package manager.

* **[NPM](https://www.npmjs.org/):** `npm install cferdinandi/social-sharing`
* **[Bower](http://bower.io/):** `bower install https://github.com/cferdinandi/social-sharing.git`
* **[Component](http://component.io/):** `component install cferdinandi/social-sharing`



## Working with the Source Files

If you would prefer, you can work with the development code in the `src` directory using the included [Gulp build system](http://gulpjs.com/). This compiles, lints, and minifies code, and runs unit tests. It's the same build system that's used by [Kraken](http://cferdinandi.github.io/kraken/), so it includes some unnecessary tasks and Sass variables but can be dropped right in to the boilerplate without any configuration.

### Dependencies
Make sure these are installed first.

* [Node.js](http://nodejs.org)
* [Ruby Sass](http://sass-lang.com/install)
* [Gulp](http://gulpjs.com) `sudo npm install -g gulp`

### Quick Start

1. In bash/terminal/command line, `cd` into your project directory.
2. Run `npm install` to install required files.
3. When it's done installing, run one of the task runners to get going:
	* `gulp` manually compiles files.
	* `gulp watch` automatically compiles files when changes are made.
	* `gulp reload` automatically compiles files and applies changes using [LiveReload](http://livereload.com/).



## Browser Compatibility

Social Sharing works in all modern browsers, and IE 6 and above.



## How to Contribute

In lieu of a formal style guide, take care to maintain the existing coding style. Don't forget to update the version number, the changelog (in the `readme.md` file), and when applicable, the documentation.



## License

Social Sharing is licensed under the [MIT License](http://gomakethings.com/mit/).



## Changelog

Social Sharing uses [semantic versioning](http://semver.org/).

* v1.7.2 - October 19, 2014
	* Updated `gulpfile.js` tasks and namespacing.
* v1.7.1 - October 3, 2014
	* Updated `gulpfile.js`.
	* Updated readme.
	* Updated travis config file.
* v1.7.0 - August 25, 2014
	* Switched from Sass Lib to Ruby Sass.
* v1.6.0 - July 29, 2014
	* Added Reddit support.
* v1.5.0 - June 23, 2014
	* Converted to gulp.js workflow.
	* Updated naming conventions.
	* Added minified versions of files.
	* Updated to three number versioning system.
	* Updated Tumblr sharing link.
* v1.4 - January 13, 2014
	* Added Tumblr support.
* v1.3 - December 6, 2013
	* Added Sass support.
* v1.2 - November 9, 2013
	* Added GitHub button.
* v1.1 - October 26, 2013
	* Added Pinterest support.
* v1.0 - June 7, 2013
	* Switched to MIT license.
* Version 1.0 - April 2, 2013
	* Initial release.
