source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'
gem 'bootstrap-sass', '~> 3.4', '>= 3.4.1'
gem 'rails', '~> 5.2.2', '>= 5.2.2.1'
gem 'jquery'
gem 'jquery-rails'
gem 'bcrypt'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'carrierwave', '~> 1.3', '>= 1.3.1'
gem 'mini_magick', '~> 4.9', '>= 4.9.3'
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  gem 'sqlite3', '~> 1.3.6'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'rails-controller-testing'
  gem 'minitest'                
  gem 'minitest-reporters'
  gem 'guard'
  gem 'guard-minitest'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

group :production do
  gem 'pg'
  gem 'fog', '~> 2.1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
