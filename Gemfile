source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages'] #, group: :jekyll_plugins

group :jekyll_plugins do
  gem 'jekyll-feed'
  gem "jekyll-github-metadata"
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
end

group :test do
  gem "html-proofer"
end
