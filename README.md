# UI Book Club Exercises Collection #

To use this project, the following must be installed on your computer:

* [Ruby](http://www.ruby-lang.org/en/)
* [RubyGems](http://rubygems.org/)
* [Bundler](http://gembundler.com/)
* [Bower](http://bower.io)

For painless web-serving, install [Pow](http://pow.cx "Pow: Zero-configuration Rack server for Mac OS X") also.

## Getting Started ##

1. Install Ruby, RubyGems, Bundler and Bower, or verify that they are already installed.
2. Change into the <code>ui-book-club-exercises/</code> directory in your favorite terminal application and type <code>bundle install</code>.
3. Install front-end dependencies by typing <code>bower install</code>.
4. Steps 1–3 are one-time-only setup requirements. Hereafter, all you need to do is run the following command from <code>css3-foundation/</code>:

        bundle exec guard

    This will monitor changes to your source files, recompile the Sass, and reload your browser. To compile the Sass files one time only, type:

        bundle exec compass compile

    More details can be found in the [Compass](http://compass-style.org/reference/compass/ "Compass Core Framework | Compass Documentation") and [Guard](http://guardgem.org "") documentation.

