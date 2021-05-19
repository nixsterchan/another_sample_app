source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'
gem 'rails', '~> 5.2.2', '>= 5.2.2.1'
gem 'puma', '~> 4.3'
gem 'sass-rails', '~> 5.0.7'
gem 'uglifier', '~> 4.1.20'
gem 'jquery-rails', '~> 4.3.3'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5.2.0'
gem 'jbuilder', '~> 2.8.0'

gem 'bcrypt', '~> 3.1.12'
gem 'carrierwave', '~> 1.3.1'
gem 'faker', '~> 1.9.3'
gem 'mini_magick', '~> 4.9.3'
gem 'will_paginate', '~> 3.1.7'
gem 'bootstrap-will_paginate', '~> 1.0.0'
gem 'bootstrap-sass', '~> 3.4.1'

gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '~> 1.3.13'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg', '~> 1.1.4'
  gem 'fog', '~> 2.1.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'

  gem 'rails-controller-testing', '~> 1.0.4'

  gem 'minitest',                 '~> 5.11.3'
  gem 'minitest-reporters',       '~> 1.3.6'

  gem 'guard',                    '~> 2.15.0'
  gem 'guard-minitest',           '~> 2.4.6'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
