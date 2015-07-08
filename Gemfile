source 'https://rubygems.org'
ruby '2.1.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0.beta4'
gem 'arel', '6.0.0.beta2'
gem 'pg', '~> 0.18.0.pre20141017160319'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.0.beta1'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '~> 2.5.3'
# Use CoffeeScript for .coffee assets and views
#gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'bcrypt', '~> 3.1.9' #to make secure password hashes
gem 'launchy', '~> 2.4.3' #to open pages automatically by 'save_and_open_page'
gem 'russian', '~> 0.6.0' # перевод рельсов на русский. сообшения об ошибках, pluralize, еще куча всего
gem 'clearance', '~> 1.6.0' #user authentication system
# Use jQuery as the JavaScript library
gem 'jquery-rails', '~> 4.0.0.beta2'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
# gem 'sdoc', '~> 0.4.0', group: :doc

#XML Parsing
gem 'nokogiri', '~>1.6.5'
#Pagination
gem 'kaminari', '~> 0.16.3'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# remove from production later
gem 'factory_girl_rails', '~> 4.5.0'
gem 'faker', '~> 1.4.3'

#image manipulation
#gem 'carrierwave', '~> 0.10.0'
#gem 'mini_magick', '~> 4.0.1'
#gem 'fog', '~> 1.26.0'
gem 'fog', '~> 1.27.0'
gem 'fog-aws', '0.1.0'
gem 'paperclip', '~> 4.2.1'
#gem 'aws-sdk', '< 2.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '~> 3.5.1'
  gem 'rspec-rails', '~> 3.1.0'
# Use sqlite3 as the database for Active Record
# Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0.0.beta4'
end

group :test do
  gem 'poltergeist', '~> 1.5.1'
  gem 'capybara', '~> 2.4.4'
end

group :production do
  gem 'rails_12factor', '0.0.3'
end

gem 'capistrano', '~> 3.1.0'
gem 'capistrano-bundler', '~> 1.1.2'
gem 'capistrano-rails', '~> 1.1.1'
gem 'capistrano-rvm', github: "capistrano/rvm"

# Add this if you're using rbenv
# gem 'capistrano-rbenv', github: "capistrano/rbenv"

# Add this if you're using rvm


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
