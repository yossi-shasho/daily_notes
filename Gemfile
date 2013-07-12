source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'
gem 'pg' # PostgreSQL
gem 'sass-rails', '~> 4.0.0'
gem 'haml' # templating engine instead of default erb
gem 'haml-rails' # makes rails auto-generate views in haml instead of erb
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'coffee-rails', '~> 4.0.0'
gem 'simple_form' # pretty bootstrap forms
gem 'bootstrap-sass', '~> 2.3.2' # Sass-powered version of Twitter's Bootstrap
gem 'font-awesome-sass-rails' #an iconic font designed for use with Twitter Bootstrap


group :development, :test do
  gem 'rspec-rails', '~> 2.0' # RSpec unit testing
  gem 'awesome_print' # better console printing (using 'ap')
end

group :test do
  gem 'spork', '~> 0.9.2'
  gem 'guard', '~> 1.7.0' # automatically run specs when files change
  gem 'guard-rspec', '~> 2.5.1' # automatically run your specs
  gem 'guard-bundler', '~> 1.0.0' # automatically install/update bundle when needed
  gem 'capybara', '~> 2.1.0' # UI tests (selenium based)
  gem 'poltergeist', '~> 1.3.0' # phantomJS drivers for rspec & capybara, for JS testing. make sure you have installed phantomJS. @see: http://railscasts.com/episodes/391-testing-javascript-with-phantomjs
                          #gem 'rb-inotify', '~> 0.8' if RUBY_PLATFORM.downcase.include?("linux")
                          #gem 'rb-fsevent', '~> 0.9' if RUBY_PLATFORM.downcase.include?("darwin")
                          #gem 'cucumber-rails', '1.3.0', :require => false # cucumber testing
  gem 'mocha', '~> 0.13.2'
  gem 'email_spec', '~> 1.4.0'
  gem 'launchy', '~> 2.2.0'
end


# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby


# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
