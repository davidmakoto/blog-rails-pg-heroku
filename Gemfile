source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"
gem "rails", "~> 7.0.4"
gem "sprockets-rails"
gem "pg", "1.3.5"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false
gem "sassc-rails"
gem "tailwindcss-rails", "~> 2.0"
gem "image_processing", "~> 1.2"
gem "devise"
gem 'cancancan'
gem 'dotenv-rails', groups: [:development, :test]


group :development, :test do
  gem 'faker', github: 'faker-ruby/faker', branch: 'main'
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "byebug", platforms: %i[ mri mingw x64_mingw ]
  gem "factory_bot_rails", "~> 6.2.0"
  gem "rspec-rails"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "shoulda-matchers"
end

group :production do
end

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]