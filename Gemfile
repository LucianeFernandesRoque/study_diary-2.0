source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

gem "rails", "~> 7.0.3", ">= 7.0.3.1"
gem "sprockets-rails"
gem 'pg', '~> 1.4', '>= 1.4.5'
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis", "~> 4.0"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem 'rspec-rails', '~> 6.0.0'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'dotenv-rails', groups: [:development, :test]
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'pry-nav'
  gem 'pry-remote'
  gem "debug", ">= 1.0.0"
  gem 'faker'
  gem 'better_errors'
  gem 'database_cleaner-active_record'
  gem 'factory_bot_rails'
end

group :development do
  gem "web-console"
end