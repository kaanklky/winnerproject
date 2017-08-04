source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'puma', '~> 3.7'
gem 'rails', '~> 5.1.2'
gem 'sass-rails', '~> 5.0'
gem 'sqlite3'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'
gem 'devise'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'will_paginate', '~> 3.1.0'
gem 'will_paginate-bootstrap'
gem 'whenever', :require => false
gem 'ransack', github: 'activerecord-hackery/ransack'
gem "paranoia", "~> 2.2"
gem 'friendly_id', '~> 5.1.0'
gem 'simple_form'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]

  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
  gem 'annotate', require: false
  gem 'faker'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'web-console', '>= 3.3.0'

  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
