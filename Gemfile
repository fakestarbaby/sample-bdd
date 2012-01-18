source 'http://rubygems.org'

gem 'rails', '3.1.3'

gem 'jquery-rails'

group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'growl'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'heroku'
  gem 'rb-fsevent', :require => false
  gem 'sqlite3'
end

group :test do
  gem 'spork', '~> 0.9.0.rc'
end

group :production do
  gem 'pg'
end

gem "rspec-rails", :group => [ :development, :test ]
