source 'https://rubygems.org'

gem 'rails', '3.2.13'

# User Management
gem 'devise'

# Admin
gem 'activeadmin'
gem 'sass-rails'
gem "meta_search",    '>= 1.1.0.pre'

# Frontend
gem 'simple_form'
gem "jquery-rails", "< 3.0.0"
gem 'flatui-rails'

# NerRelic statistics ( Free Heroku add-on )
gem 'newrelic_rpm'

group :development, :test do
  gem 'rspec-rails', '~> 2.0'

  # Test and development database
	gem 'sqlite3'
end

group :production do
  gem 'pg'
  gem 'unicorn'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
