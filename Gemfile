ruby ENV['CUSTOM_RUBY_VERSION'] || '2.2.2'
source 'https://rubygems.org'

gem 'activeadmin', '~> 1.0.0.pre1'
gem 'bower-rails', '~> 0.9.0'
gem 'carrierwave', '~> 0.10.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'devise', '~> 3.5.1'
gem 'draper', '~> 2.1.0'
gem 'fog', '~> 1.31.0', require: 'fog/aws/storage'
gem 'haml', '~> 4.0.4'
gem 'kaminari', '~> 0.16.1'
gem 'mini_magick', '~> 4.2.1'
gem 'newrelic_rpm', group: [:development, :production]
gem 'nokogiri', '~> 1.6.6.2'
gem 'pg', '~> 0.18.1'
gem 'rack-timeout'
gem 'rails', '~> 4.2.0'
gem 'sass-rails', '~> 5.0.1'
gem 'uglifier', '~> 2.7.0'
gem 'unf', '~> 0.1.4'
gem 'unicorn', '~> 4.9.0'
gem 'utf8-cleaner', '~> 0.0.9'

group :test, :development do
  gem 'capybara'
  gem 'dotenv-rails'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'pry'
  gem 'rspec-rails'
end

group :test do
  gem 'capybara-screenshot'
  gem 'codeclimate-test-reporter', require: false
  gem 'curb'
  gem 'database_cleaner'
  gem 'poltergeist'
  gem 'shoulda-matchers', '~> 2.8.0', require: false
  gem 'simplecov'
  gem 'webmock'
end

group :development do
  # gem 'coffee-rails-source-maps'
  # gem 'sass-rails-source-maps'
  gem 'bullet'
  gem 'foreman'
  gem 'guard'
  gem 'guard-livereload'
  gem 'guard-rspec', require: false
  gem 'overcommit'
  gem 'rb-fchange', require: false
  gem 'rb-fsevent', require: false
  gem 'rb-inotify', require: false
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'travis'
end

group :production do
  gem 'skylight', '~> 0.6.0'
  gem 'rails_12factor', '0.0.3'
  gem 'bugsnag'
  gem 'heroku_rails_deflate'
end
