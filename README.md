# Curriculum-Vitml

This is a Ruby, SCSS, Slim based personal resume generator.

Prerequisites:
* Ruby 2.1.2, Bundler
* NPM, Bower

Usage:
* `git clone https://github.com/dliggat/curriculum-vitml.git`
* `cd curriculum-vitml`
* `bundle install`
* `bower install`
* `bundle exec middleman server`
* Visit http://localhost:4567
* Edit and create additional `source/content` slim partials as necessary
  * Ensure they are linked from `index.html.slim`
* Optional: print the resulting page to PDF (tested in Chrome)
* Optional: generate a HTML payload: `bundle exec middleman build`
