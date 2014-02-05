source 'http://rubygems.org'

gem 'rails', '3.2.16'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# Gems used for interfacing with the database

group :production do
  gem 'pg'
end
group :development, :test do
  gem 'sqlite3'
end

# Template engines

gem 'haml'

# Asset template engines

gem 'json'
gem 'sass'
group :production do
  # gem 'execjs' #javascript executable
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'jquery-rails'
  gem 'jquery-ui-rails'
  gem 'uglifier'
end

gem "ducksboard", :git => 'git://github.com/jhsu/ducksboard.git'

# Use thin as the production web server
# group :production do
#  gem 'thin'
# end

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end

# Miscellaneous
gem 'inherited_resources'
gem 'has_scope'
gem 'gravtastic'
gem 'trueskill'
gem 'kaminari'
gem 'coffee-filter'
gem 'bcrypt-ruby', '~> 3.0.0'
