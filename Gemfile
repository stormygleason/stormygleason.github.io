# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll"
gem "jekyll-theme-chirpy", "~> 7.3"

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
group :jekyll_plugins do
gem 'debug'
gem 'jekyll-compose'
gem 'http',"4.4.1"
gem "sass-embedded"
gem "nokogiri"  
# gem 'mastodon-api', :git => 'https://github.com/mastodon/mastodon-api.git'
# gem 'mastodon-social'
end