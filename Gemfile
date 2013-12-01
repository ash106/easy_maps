source 'https://rubygems.org'

ruby '2.0.0'

gem 'rails', '3.2.15'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'gmaps4rails'
gem 'underscore-rails'
gem 'jquery-rails'
gem 'cancan'
gem 'devise'
gem 'figaro'
gem 'foundation-rails'
gem 'pg'
gem 'rolify'
gem 'simple_form'
gem 'unicorn'

group :development do
  gem 'powder'
  gem 'pry-rails'
  gem 'pry-theme'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
  gem 'xray-rails'
  gem 'letter_opener'
  gem 'guard'   # Use `guard init` to setup
  gem 'rb-fsevent', require: false
  gem 'guard-pow' 
  gem 'guard-minitest'
  gem 'guard-livereload' 
  gem "rack-livereload" # Need to put `config.middleware.use Rack::LiveReload` in your config/environments/development.rb file
  gem 'ruby_gntp'
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'rails_layout'
  gem 'rb-fchange', :require=>false
  gem 'rb-fsevent', :require=>false
  gem 'rb-inotify', :require=>false
end

group :development, :test do
  gem "minitest-rails", github: 'blowmage/minitest-rails'
  gem "factory_girl_rails", ">= 4.2.0"
  gem 'ffaker'
  # gem "email_spec"
end

# group :test do
#   gem 'minitest-spec-rails'
#   gem 'minitest-wscolor'
# end
