source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '>=3.2.2'

gem 'rails', '~> 7.0.4', '>= 7.0.4.3'

gem 'sprockets-rails'

gem 'rails_12factor', group: :production


gem 'sqlite3', group: :development
gem 'pg', '~> 1.1', group: :production

gem 'puma', '~> 5.0'

gem 'importmap-rails'

gem 'turbo-rails'

gem 'stimulus-rails'

gem 'jbuilder'

gem 'dotenv-rails', require: 'dotenv/rails-now'

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

gem 'bootsnap', require: false

gem 'rack-cors'

gem 'devise'
gem 'devise-jwt'
gem 'jsonapi-serializer'

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails'
end

group :development do
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
gem 'rswag'
