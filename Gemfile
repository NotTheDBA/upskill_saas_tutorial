source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.2.3'

# Use Puma as the app server
gem 'puma', '4.2.1'
# Use SCSS for stylesheets
gem 'sass-rails', '6.0.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '4.2.0'
#adding coffeescript for heroku
gem 'coffee-script-source', '1.12.2'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '5.0.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use devise gem to manage user authentication.
gem 'devise', '4.7.1'

# Use jquery as the JavaScript library
gem 'jquery-rails', '4.3.5'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '5.2.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.9.1'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use Twitter Boostrap for dynamic layout and styling
gem 'bootstrap-sass', '3.4.1'

# Use FontAwesome for adding icons.
gem 'font-awesome-sass', '5.11.2'

# Use Hirb gem for better console data presentation
gem 'hirb', '0.7.3'

# Use Stripe for payment processing
gem 'stripe', '5.7.0'

# Use Figaro for ENV variables
gem 'figaro', '1.1.1'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
end

group :production do
  #Use the PostGRES sql in production.
  gem 'pg','1.1.4'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '3.2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '2.0.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

ruby '2.3.0'