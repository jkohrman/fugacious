source 'http://rubygems.org'

gem 'rails', '3.2.3'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

#gem 'bartt-ssl_requirement', :require => 'ssl_requirement'
gem 'capistrano'
gem 'devise'
gem 'exception_notification', :require => 'exception_notifier'
gem 'knife-solo'
gem 'knife-ec2'
gem 'nifty-generators'
# gem 'paperclip'
# gem 'redbox'


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
group :development do
  gem "nifty-generators"
  gem 'sqlite3'
end

group :production do
#  gem 'memcache-client'
#  gem 'memcached'
  gem 'mysql2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', " ~> 3.2.3"
  gem 'coffee-rails', " ~> 3.2.1"
  gem 'uglifier'
end

gem 'jquery-rails'