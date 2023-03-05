source "https://rubygems.org"

# A DSL for quickly creating web applications
# https://github.com/sinatra/sinatra
#gem "sinatra", "~> 2.1"
gem 'sinatra', '~> 3.0', '>= 3.0.5'

# An object-relational mapper
# https://guides.rubyonrails.org/active_record_basics.html
#gem "activerecord", "~> 6.1"
gem 'activerecord', '~> 7.0', '>= 7.0.4.2'

# Configures common Rake tasks for working with Active Record
# https://github.com/sinatra-activerecord/sinatra-activerecord
#gem "sinatra-activerecord"
gem 'sinatra-activerecord', '~> 2.0', '>= 2.0.26'

# Rack middleware. Used specifically for parsing the request body into params.
# https://github.com/rack/rack-contrib
#gem "rack-contrib", "~> 2.3"
gem 'rack-contrib', '~> 2.3'

# Run common tasks from the command line
# https://github.com/ruby/rake
gem "rake"

# Provides functionality to interact with a SQLite3 database
# https://github.com/sparklemotion/sqlite3-ruby
#gem "sqlite3", "~> 1.4"
gem 'sqlite3', '~> 1.6', '>= 1.6.1'

# Require all files in a folder
# https://github.com/jarmo/require_all
#gem "require_all"
gem 'require_all', '~> 3.0'


gem 'puma', '~> 6.1', '>= 6.1.1'
gem 'thin', '~> 1.8', '>= 1.8.1'
gem 'falcon', '~> 0.42.3'
gem 'webrick', '~> 1.8', '>= 1.8.1'

# These gems will only be used when we are running the application locally
group :development do
  # Used to generate seed data
  # https://github.com/faker-ruby/faker
  #gem "faker", "~> 2.18"
  gem 'faker', '~> 3.1', '>= 3.1.1'


  # Auto-reload the server when files are changed
  # https://github.com/alexch/rerun
  gem "rerun"

  gem "pry"
end

# These gems will only be used when we are running tests
group :test do
  gem "database_cleaner"
  gem "rspec"
  gem 'rack-test', '~> 2.0', '>= 2.0.2'
  # gem "rspec-json_expectations", "~> 2.2"
  gem 'rspec-json_expectations', '~> 2.2'
end


