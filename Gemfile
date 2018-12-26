source 'https://rubygems.org'

gem 'rails', '5.2.2'      # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'puma'                # Use Puma as the app server
gem 'sass-rails'          # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3.0'  # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails'        # Use CoffeeScript for .coffee assets and views

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'hamlit'              # Use haml syntax through hamlit
gem 'foundation-rails'    # Use Zurb Foundation as front-end framework

# Use locale from browser
# gem 'http_accept_language'

gem 'jquery-rails'        # Use jquery as the JavaScript library
gem 'turbolinks'          # Turbolinks makes navigating your web application faster
                          # Read more: https://github.com/turbolinks/turbolinks
gem 'jbuilder', '~> 2.0'  # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

# gem 'redis', '~> 3.0'   # Use Redis adapter to run Action Cable in production
# gem 'bcrypt', '~> 3.1.7'  # Use ActiveModel has_secure_password

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'byebug'            # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'sqlite3'           # Use sqlite3 as the database for Active Record
end

group :development do
  gem 'web-console'       # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'listen', '~> 3.1'
  gem 'spring'            # Spring speeds up development by keeping your application running in the background
                          # Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg'                # Use postgresql as the database
  gem 'rails_12factor'    # Use 12 factor
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

ruby '2.5.3'              # Require Ruby version