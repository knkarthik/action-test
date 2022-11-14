# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.5'

gem 'aasm'
gem 'activemodel-serializers-xml'
gem 'activerecord-import'
gem 'active_storage_validations'
gem 'ahoy_email'
gem 'aws-sdk-s3'
gem 'bootsnap', '>= 1.1.0', require: false # Reduces boot times through caching; required in config/boot.rb
gem 'business_time'
gem 'composite_primary_keys'
gem 'daemons'
gem 'ddtrace', '~> 1.0.0.beta1'
gem 'delayed_job_active_record'
gem 'devise'
gem 'doorkeeper'
gem 'doorkeeper-i18n'
gem 'geocoder'
gem 'globalize', git: 'https://github.com/globalize/globalize'
gem 'google-protobuf'
gem 'holidays'
gem 'jbuilder', '~> 2.11' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jsonapi-authorization', git: 'https://github.com/financeit/jsonapi-authorization', branch: 'v3.0.1_centah'
gem 'jsonapi-resources', git: 'https://github.com/financeit/jsonapi-resources', branch: 'v0.9.10_centah'
gem 'lockbox'
gem 'lograge'
gem 'mini_magick'
gem 'nylas'
gem 'oj'
gem 'omniauth'
gem 'omniauth-jwt'
gem 'omniauth-rails_csrf_protection'
gem 'percy-capybara', '~> 5.0.0'
gem 'pg', '>= 0.18', '< 2.0' # Use postgresql as the database for Active Record
gem 'phonelib', require: false
gem 'puma', '~> 5.6' # Use Puma as the app server
gem 'pundit', git: 'https://github.com/financeit/pundit', branch: 'v2.0.1_centah'
gem 'rails', '~> 6.0.4'
gem 'redis'
gem 'request_store'
gem 'rest-client', require: false
gem 'rollbar'
gem 'rswag-api'
gem 'rubyXL'
gem 'searchkick'
gem 'seed-fu', '~> 2.3'
gem 'sequenced'
gem 'timezone', '~> 1.3'
gem 'turbolinks', '~> 5' # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'twilio-ruby', require: false
gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets

gem 'flamegraph', git: 'https://github.com/thisduck/flamegraph', require: false
gem 'stackprof', require: false

gem 'ahoy_matey'

gem 'jwt', require: false

group :development, :test do
  gem 'brakeman', require: false
  gem 'capybara', require: false
  gem 'capybara-screenshot', require: false
  gem 'database_cleaner'
  gem 'factory_bot_rails'
  gem 'faker', git: 'https://github.com/stympy/faker.git', branch: 'master'
  gem 'jazz_fingers'
  gem 'parallel_tests'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'pry-rescue', require: false
  gem 'pry-stack_explorer'
  gem 'rspec-rails', '~> 5.1'
  gem 'rswag-specs'
  gem 'selenium-webdriver', require: false
  gem 'site_prism', '~> 3.7', require: false
  gem 'thin', require: false
  gem 'timecop', require: false
  gem 'vcr'
  gem 'webdrivers', '~> 4.7', require: false
  gem 'webmock'
end

group :test do
  gem 'simplecov', require: false
  gem 'simplecov_json_formatter', require: false
  gem 'test-prof'
end

group :development do
  gem 'letter_opener'
  gem 'listen', '>= 3.0.5', '< 3.8'
  gem 'pronto'
  gem 'pronto-flay', require: false
  gem 'pronto-rubocop', require: false
  gem 'rack-cors'
  gem 'spring' # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0' # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
end

group :development, :deploy do
  gem 'bcrypt_pbkdf'
  gem 'ed25519'
end

group :deploy do
  gem 'capistrano', '~> 3.16', require: false
  gem 'capistrano-bundler', '~> 2.0', require: false
  gem 'capistrano-ember_cli', require: false
  gem 'capistrano-npm', require: false
  gem 'capistrano-passenger', require: false
  gem 'capistrano-rails', '~> 1.6', require: false
  gem 'capistrano-rvm', require: false
  gem 'whenever'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

gem 'log_formatter'
