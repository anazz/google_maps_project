source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.3.4'

source 'https://rubygems.org'

# authentification
#gem 'devise'
#gem 'pundit'

gem 'rails'
gem 'puma'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
gem 'sdoc'

group :development, :test do
  gem 'sqlite3'
  gem 'byebug',  '9.0.6', platform: :mri
 #gem 'rspec-rails'
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'database_cleaner'
  gem "factory_bot_rails"
  gem 'simplecov'
  gem 'dotenv-rails', require: 'dotenv/rails-now'
end

group :development do
  gem "better_errors"
  gem "binding_of_caller"
  gem 'letter_opener'
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'capybara'
  gem 'poltergeist'
  gem 'shoulda-matchers'
end

group :production do
  gem 'pg', '0.20.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'devise'

gem 'bootsnap', '>= 1.1.0', require: false

gem 'dotenv-rails'

gem 'stripe'

gem 'mailjet'