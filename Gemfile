source 'https://rubygems.org'

 ruby '2.6.5'

gem 'dotenv-rails' # For reading .env files
gem 'twitter' # For communicating with the Twitter API
gem 'activerecord' # ORM for the PostgreSQL db
gem 'standalone_migrations', '~> 5.2','>= 5.2.7' # For database migrations
gem 'pg' # PostgreSQL

group :development, :test do
    # Use pry for debugging
    gem 'pry', '~> 0.12.2'
    gem 'pry-rescue'
    gem 'pry-stack_explorer'
    gem 'pry-byebug'
end

group :test do
    gem 'minitest'
    gem 'minitest-reporters' # Makes our test report look nice!
end