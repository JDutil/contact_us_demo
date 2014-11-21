source 'https://rubygems.org'
ruby '2.1.5'

gem 'rails', '~> 4.1.8'
gem 'rails_12factor'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'contact_us', '~> 0.5.4'
gem 'formtastic'
gem 'sass-rails', '~> 4.0.2'

group :production do
  gem 'pg'
end
group :development, :test do
  gem 'sqlite3'
end

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19', :require => 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
  gem "capybara", '~> 2.2.1'
  gem "rspec-rails", "~> 2.14.2"
  gem 'selenium-webdriver'
  gem "simplecov"
end
