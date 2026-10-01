source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#

# Enforcing supported GitHub Pages versions (Jekyll 3.10.0)
# https://pages.github.com/versions/
gem "jekyll", "3.10.0"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "just-the-docs"

# Required for Ruby 3.x (webrick was removed from stdlib)
gem "webrick"

# Markdown/highlighting versions used by GitHub Pages (github-pages 232)
gem "kramdown", "2.4.0"
gem "kramdown-parser-gfm", "1.1.0"
gem "rouge", "3.30.0"

# rubyzip < 3.4.0 is vulnerable to path traversal (pulled in by jekyll-remote-theme).
# The github-pages gem pins jekyll-remote-theme 0.4.3 (rubyzip < 3.0), so the
# GitHub Pages plugins are listed individually below instead of using github-pages.
gem "rubyzip", ">= 3.4.0"

# If you have any plugins, put them here!
# Plugins enabled by GitHub Pages by default, at the github-pages 232 versions.
group :jekyll_plugins do
  gem "jekyll-coffeescript", "1.2.2"
  gem "jekyll-commonmark-ghpages", "0.5.1"
  gem "jekyll-default-layout", "0.1.5"
  gem "jekyll-gist", "1.5.0"
  gem "jekyll-github-metadata", "2.16.1"
  gem "jekyll-include-cache", "0.2.1"
  gem "jekyll-optional-front-matter", "0.3.2"
  gem "jekyll-paginate", "1.1.0"
  gem "jekyll-readme-index", "0.3.0"
  gem "jekyll-relative-links", "0.6.1"
  gem "jekyll-remote-theme", "~> 0.6"
  gem "jekyll-seo-tag", "2.8.0"
  gem "jekyll-titles-from-headings", "0.5.3"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]