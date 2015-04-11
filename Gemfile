source 'https://rubygems.org'

ruby '2.2.0'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
gem 'bootstrap-sass'
gem 'bcrypt'
# Use sqlite3 as the database for Active Record
group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'guard-rspec'
  gem 'spork', github: 'sporkrb/spork'
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara', '2.2.0'
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :doc do
  gem 'sdoc', require: false
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

