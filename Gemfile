source 'https://rubygems.org'

ruby '2.1.0'

gem 'rails', '4.0.3'

# Heroku works best with PostgreSQL
# We'll run it on prod and dev.
gem 'pg' 

gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  gem 'sdoc', require: false
end

group :production do
  gem 'rails_12factor'
end


## Our additions below

gem 'sass-rails', '~> 4.0.0' # SCSS for styling

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :test do
  gem 'rspec-rails'
  gem 'capybara', '~> 2.3.0'
  gem 'database_cleaner'
  gem 'factory_girl_rails', '~> 4.0'
  gem 'pry-rails'
end

# For installing HAML and HAML generators
# Read more - https://bloc.io/resources/using-haml
gem 'haml-rails' # Comment if you'd rather use ERB