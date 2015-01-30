# Curriculum-Vitml

This is a personal resume static-HTML generator based on Ruby-Middleman, SCSS, and the Slim templating language. An overview of the motivation for this can be found [on my site](http://liggat.org/2015/01/30/personal-cvs-with-curriculum-vitml/).

Prerequisites (documentation abounds for installing these on your platform of choice):
* Ruby 2.1.2, Bundler
* NPM, Bower

Usage:
* `git clone https://github.com/dliggat/curriculum-vitml.git`
* `cd curriculum-vitml`
* `bundle install`
* `bower install`
* `bundle exec middleman server`
* Visit [http://localhost:4567](http://localhost:4567)
* Edit and create additional `source/content` slim partials as necessary
  * Ensure they are linked from `index.html.slim`
* Optional: print the resulting page to PDF (tested in Chrome)
* Optional: generate a HTML payload: `bundle exec middleman build`
