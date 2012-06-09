source 'https://rubygems.org'

gem 'rails', '3.2.5'

group :development do
  #gem 'sqlite3', '1.3.5' --> removed to use PostgreSQL instead of SQLite
  gem 'rspec-rails',      ">= 2.0.0.beta"
  gem 'pg', '0.12.2' #-> added to use PostgreSQL instead of SQLite
  gem 'guard-rspec', '0.5.5'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'

  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.0'

group :production do
  gem 'pg', '0.12.2'
end

group :test do
  gem 'capybara'
  gem 'launchy'
  gem 'rb-fsevent', '0.4.3.1', :require => false
  gem 'growl', '1.0.3'
end

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
