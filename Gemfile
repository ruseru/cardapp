source 'https://rubygems.org'

ruby '2.3.3'

gem 'unicorn' # make sure you follow installation instructions for this gem

group :production do
  #gem 'pg' # dont want sqlite in production
  gem 'rails_log_stdout',           github: 'heroku/rails_log_stdout'
  gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
end

group :development, :test do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'byebug', platform: :mri
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :assets do
  gem 'sass-rails', '5.0.6'
  gem 'coffee-rails', '4.2.1'
  gem 'uglifier', '3.0.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem 'pg', '0.19.0'
#gem 'puma', '~> 3.0'

# Use jquery as the JavaScript library
gem 'jquery-rails', '4.2.1'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development




