source 'https://rubygems.org'

ruby '2.1.5'

gem 'rails'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :development do
  gem 'sqlite3'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier'
end

gem 'jquery-rails'

gem 'feedjira'

gem 'feed_searcher'
gem 'kaminari'
gem 'kaminari-bootstrap'
gem 'devise'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

gem 'bootstrap-sass'

gem 'haml-rails'

group :development, :test do
  gem 'erb2haml'
  gem 'rspec-rails'
  gem 'capybara'
end

group :test do
  gem 'shoulda-matchers'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'factory_girl_rails'
end

gem 'whenever', :require => false
