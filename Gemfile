source 'https://rubygems.org'

gem 'rails', '3.2.7'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'

  gem 'compass-rails'
  gem 'compass-h5bp', git: 'git://github.com/sporkd/compass-h5bp.git' # use image replacement
  gem 'susy', '~> 1.0'
end

gem 'unicorn'
gem 'exception_notification'
gem 'haml', '~> 3.2.0.beta.2'

group :development do
  gem "awesome_print"
  gem 'haml-rails'
  gem 'jquery-rails'
  gem 'spine-rails'
  gem 'ruby-haml-js'
  gem 'rvm-capistrano', '~> 1.2.5'
  gem 'guard-livereload'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'guard-bundler'
  gem 'guard-unicorn'
  gem 'letter_opener'
end

group :test do
  gem "rspec-rails"
  gem "factory_girl_rails"
  gem 'capybara'
  gem 'database_cleaner'
end
