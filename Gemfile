# frozen_string_literal: true

source "https://rubygems.org"
gemspec

group :jekyll_plugins do
    # gem 'wdm', '>=0.1.0'
    gem "jekyll-feed", "~> 0.6"
    gem "jekyll-sitemap"
    gem "jekyll-paginate"
    gem "jekyll-seo-tag"
    gem 'jekyll-redirect-from'
    gem "webrick"
    require 'rbconfig'
        gem 'wdm', '>= 0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i
end
