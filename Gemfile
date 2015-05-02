source 'https://rubygems.org'

ruby '2.1.5'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'
gem "heroku" 

gem 'addressable', '~> 2.3.6'

gem 'excon', '~> 0.42.1'



gem 'autoprefixer-rails'
gem 'bootstrap-sass', '~> 3.3.1'
gem 'devise'
gem 'carrierwave', '~> 0.10.0'
gem 'mini_magick', '~> 4.0.0'
gem 'acts-as-taggable-on', '~> 3.4.2'
gem 'punching_bag'
gem 'sass-rails', '~> 4.0.3'
gem 'rails-timeago', '~> 2.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

gem 'rake', '~> 10.4.2'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
gem 'jquery-turbolinks', '~>2.1.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]

group :development, :test do
  gem 'sqlite3'
end
group :production do
  gem 'pg'
  gem 'thin'
  gem 'unicorn'
end
gem 'rails_12factor', group: :production
